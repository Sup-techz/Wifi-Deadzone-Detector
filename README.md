**Wi-Fi Dead Zone Detector | Web Development & Machine Learning Project**

Developed a web-based Wi-Fi Dead Zone Detection System that analyzes network performance to identify areas with poor Wi-Fi connectivity. Since web browsers generally restrict direct access to device-level Wi-Fi signal strength measurements (RSSI in dBm), the system uses lightweight packet-based network measurements to estimate connectivity quality through parameters such as latency, packet response behavior, and frequency-related network information where available.

The system evaluates network performance to help identify potential Wi-Fi dead zones and assess connectivity across different locations. It also integrates a **Random Forest machine learning classifier** that categorizes network conditions into three classes: **Dead, Moderate, and Good**, based on the collected network data.

**Key Features:**
- **Browser-Based Detection:** Provides a web interface for analyzing Wi-Fi connectivity without requiring a dedicated native mobile application.
- **Packet-Based Analysis:** Uses small data packets and their response characteristics to assess network performance.
- **Network Metrics:** Analyzes latency and packet response behavior, with frequency and signal-related estimates where supported by the implementation.
- **Dead Zone Identification:** Helps identify areas with poor or unreliable connectivity.
- **Machine Learning Integration:** Uses a Random Forest classifier to predict network quality across three categories: Dead, Moderate, and Good.
- **Visual Network Assessment:** Presents network quality results in an accessible format to help users understand connectivity conditions.

**Technologies:** Web Development, Python, Machine Learning, Random Forest Classification, Network Performance Analysis.
