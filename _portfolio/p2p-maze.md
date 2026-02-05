---
title: "P2P Maze Game"
excerpt: "A fault-tolerant peer-to-peer multiplayer maze game with real-time state synchronization<br/>"
collection: portfolio
---

## Overview

A distributed multiplayer maze game built with **Java** that demonstrates advanced concepts in distributed systems and peer-to-peer networking.

## Key Features

- **Fault-Tolerant Architecture**: Designed to handle node failures gracefully without disrupting gameplay
- **Real-Time State Synchronization**: Multi-threaded implementation ensures consistent game state across all peers
- **Mutual Exclusion**: Ensures consistent multiplayer state even with concurrent player actions
- **Async UI**: Built an asynchronous user interface for displaying scores, player positions, and treasures in real-time

## Technologies Used

- Java
- Distributed Systems Principles
- Multi-threading & Concurrency
- Peer-to-Peer Networking
- Mutual Exclusion Algorithms

## Technical Highlights

The game implements a fully decentralized architecture where each player's client acts as both a server and client. This eliminates single points of failure and enables the game to continue even when players disconnect unexpectedly.

The mutual exclusion mechanism ensures that conflicting operations (like two players trying to collect the same treasure) are handled correctly, maintaining game integrity across all connected peers.
