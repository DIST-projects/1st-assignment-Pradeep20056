# Distributed Systems Assignments

This repository contains a collection of assignments and projects focused on Distributed Systems, covering key concepts such as Remote Method Invocation (RMI), Remote Procedure Calls (RPC), Cloud Infrastructure, and Peer-to-Peer (P2P) systems.

## 🚀 Projects Overview

### 1. RMI (Remote Method Invocation)
A Java-based implementation of a Compute Service using RMI.
- **Features**: Matrix multiplication and prime number calculation.
- **Directory**: `RMI/`
- **Key Files**:
  - `ComputeService.java`: The remote interface.
  - `ComputeServiceImpl.java`: Implementation of the interface.
  - `RMIServer.java`: Server setup and registry binding.
  - `RMIClient.java`: Client for invoking remote methods.

### 2. RPC (Remote Procedure Call)
A Python-based implementation of an RPC system using a custom HTTP-based protocol.
- **Features**: Matrix multiplication and prime number calculation via HTTP POST requests.
- **Directory**: `RPC/`
- **Key Files**:
  - `rpc_server.py`: HTTP server handling procedure calls.
  - `rpc_client.py`: Client for making requests to the server.

### 3. Torrent Assignment (P2P)
A peer-to-peer file sharing application.
- **Directory**: `Torrent assignment/`
- **Structure**:
  - `Sender/`: Handles file distribution.
  - `Receiver/`: Handles file acquisition.
  - `notes.torrent`: Sample torrent metadata file.

### 4. Cloud - Setup
Documentation and logs for setting up a distributed environment on Azure VMs.
- **Directory**: `Cloud - Setup/`
- **Content**: Includes screenshots of inbound rules, server logs, and remote connections.

---

## 🛠️ How to Run

### Java RMI
1. Compile the Java files:
   ```bash
   javac RMI/*.java
   ```
2. Start the RMI Registry:
   ```bash
   rmiregistry
   ```
3. Run the Server:
   ```bash
   java RMI.RMIServer
   ```
4. Run the Client:
   ```bash
   java RMI.RMIClient
   ```

### Python RPC
1. Run the Server:
   ```bash
   python RPC/rpc_server.py
   ```
2. Run the Client:
   ```bash
   python RPC/rpc_client.py
   ```

---

## 📝 Assignments Details
Each project includes a detailed report or documentation (PDF) within its respective directory providing further insights into the implementation and results.

---
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/BLFxgtNd)
