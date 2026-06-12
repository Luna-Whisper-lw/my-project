# TCP/IP 协议栈四层模型

```mermaid
flowchart TD
    A["Application Layer
    HTTP FTP SMTP DNS"]
    B["Transport Layer
    TCP"]
    C["Internet Layer
    IP"]
    D["Network Access Layer
    Ethernet Wi-Fi"]
    A --> B --> C --> D