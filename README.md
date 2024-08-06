# Rust MQTT Broker (MQTT 3.1.1)

## Overview
This project is an MQTT 3.1.1 broker implemented in Rust. It was developed as a two-week school project by [Daniel Vuust](https://github.com/DanielVuust), [RTK-Umbraco](https://github.com/RTK-Umbraco), and myself.
This repository is a copy of [mqtt_broker](https://github.com/DanielVuust/mqtt_broker) which is the source repository for our project.

## Project Background
This broker aims to provide a lightweight and efficient MQTT broker solution. The project focuses on demonstrating the capabilities of Rust in handling network protocols efficiently.

## Features
- **Lightweight Broker**: Optimized for minimal resource consumption.
- **MQTT 3.1.1 Compliance**: Only supports core features of MQTT 3.1.1 protocol for IoT communications (given project time constraint).

## Installation
To install and run this MQTT broker, follow these steps:

```bash
# Clone the repository
git clone https://github.com/DanielVuust/mqtt_broker
cd mqtt_broker

# Compile and run the broker
cargo build --release
./target/release/mqtt_broker
cargo run --release
