# 🚀 **Smart City Digital Twin Tool (SCDTT)**  
**A CLI tool enabling real-time simulation, monitoring, and analysis for smart city infrastructures.**

SCDTT empowers you to simulate, analyze, and monitor smart city environments in real-time. This scalable, flexible tool is designed for both educational and operational use, making it perfect for urban data scientists, researchers, and smart city developers.

![Smart City Visualization](https://example.com/path/to/your/image.png)

## 🌟 Key Features

- **Command-Line Efficiency**: Streamlined CLI for high-speed, low-resource performance.
- **City-Scale Simulation**: Emulate smart city infrastructures and interactions between IoT devices.
- **Realistic Data Generation**: Produce or input real-time sensor data.
- **Continuous Data Monitoring**: Enable real-time data tracking and alerting.
- **Scalable Integration**: Compatible with Big Data and machine learning platforms.
- **Customizable for Smart City Needs**: Adaptable for various city applications like traffic, energy, and public safety.

---

## 💻 Development Environment

The tool was created using Visual Studio Code and is compatible with any Python-supported platform.

---

## 🛠️ Getting Started with SCDTT

### Step 1: Access the Code

Download the code from OneDrive:

[Download Code from OneDrive](https://alumniuaeuac-my.sharepoint.com/:f:/r/personal/nandanaj_uaeu_ac_ae/Documents/IoT-Edu-ML-Stream?csf=1&web=1&e=ZowPbV)

#### Access Requirements:  
Please email Nandana Jayachandran at UAEU: [700046308@uaeu.ac.ae](mailto:700046308@uaeu.ac.ae) for access.

### Folder Contents Overview:

- **`init.py`**: Initializes the SCDTT environment.
- **Kafka Files**:
  - `producer.py`: Sends Kafka messages.
  - `consumer.py`: Receives Kafka messages.
  - `shared_kafka_topic.txt`: Kafka topic information.
  - `stream.py`: Manages data streaming.
  - `kafka.py`: Main Kafka handler.
- **Data Generation Files**:
  - `data_generation.py`: Generates realistic sensor data.
  - `trained_model.pkl`: Pre-trained model for predictive analytics.
- **Configuration Files**:
  - `config.yaml`: Central configuration settings.
  - `utils.py`: Utility functions for the tool.
  - **Images**: Visual assets for enhancing CLI output.

---

### Step 2: Install Required Python Packages

Ensure you have the following prerequisites installed:

- **Python 3.10.12**  
  [Download Python](https://www.python.org/downloads/)  
  If needed, install `pip`:
  ```bash
  python -m ensurepip --upgrade

- **Kafka 3.6.0**:  
  [Download Kafka](https://kafka.apache.org/downloads)  
  Follow the [Kafka Quickstart Guide](https://kafka.apache.org/quickstart) for setup.

- **MQTT - mosquitto 2.0.11**:  
  - We use the `paho-mqtt` library for MQTT protocol.
  - Install via `pip`:
    ```bash
    pip install paho-mqtt
    ```

### Step 3: Start Kafka Server

Refer to the [Kafka Quickstart Guide](https://kafka.apache.org/quickstart) for detailed instructions.

### Step 4: Run the Tool

To start SCDTT:
```bash
python main.py
```

---

With SCDTT, experience a fully customizable, scalable toolset built for smart city emulation and real-time digital twin applications. Perfect for urban data scientists, researchers, and smart city developers.
