# Wazuh-SIEM-
<img width="1125" height="595" alt="image" src="https://github.com/user-attachments/assets/329d9d07-ddf5-4fe1-9328-c42db02eba96" />
As the first step, Wazuh was installed through the terminal, and the dashboard was successfully accessed using the configured port number.
<img width="1125" height="589" alt="image" src="https://github.com/user-attachments/assets/0730b73d-7bdf-412c-9bac-70592d74950d" />
<img width="1125" height="592" alt="image" src="https://github.com/user-attachments/assets/76370fa4-7d72-4740-b981-a145f8c85240" />
In the subsequent step, endpoint agents were added by entering the IP addresses of the available devices, allowing them to securely register with the Wazuh manager for monitoring and analysis.
<img width="1125" height="591" alt="image" src="https://github.com/user-attachments/assets/3b16e1d8-f396-4070-b8a7-4487a607abb5" />
<img width="1125" height="589" alt="image" src="https://github.com/user-attachments/assets/12926764-e1a6-4a32-a3ed-d83dd5b05fd1" />
During the testing phase, the original directory paths were manipulated and mapped to a controlled testing path to evaluate monitoring and alerting behavior.
<img width="1125" height="591" alt="image" src="https://github.com/user-attachments/assets/c6778137-3634-498e-927a-2c2b3afd57bc" />
Upon creating a new file in the monitored directory, Wazuh automatically generates a log event, allowing real-time tracking and verification of device-level activities to strengthen security monitoring.

This project successfully demonstrated the deployment and configuration of the Wazuh security monitoring solution, including agent integration and real-time file activity monitoring. By configuring directory path monitoring and validating log generation through controlled file creation, the system effectively proved its capability to detect and record endpoint-level changes. This implementation enhances visibility, strengthens security monitoring, and ensures improved threat detection across connected devices.
