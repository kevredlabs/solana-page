# Security Policies

At Kevred, the protection of our blockchain validator nodes and the servers under our management is crucial. This guide outlines the security tactics and protocols we deploy to secure our infrastructure.

> **Note:** Please be aware that the Solana staking program does not permit validators to access the staked SOL tokens at any time. You maintain complete control and custody of your SOL.


## Server Setup

- **Robust Configuration**: The validator server is configured to meet top industry standards, with unnecessary services and ports disabled to reduce exposure to vulnerabilities. It is hosted on [Edgevana's infrastructure](https://www.edgevana.com).
- **Frequent Security Updates**: We regularly update our systems with the latest security patches to defend against emerging threats.
- **Monitoring**: Monitoring system is hosted on a separate server.
- **Skilled Team**: Our team possesses deep expertise and professional experience in managing and securing blockchain infrastructure, ensuring a stable and secure environment.



## SSH Security Measures

- **SSH Key Authentication**: We exclusively use key-based authentication for accessing our servers at Kevred, with password access completely disabled.
- **Brute Force Protection**: We enhance our security framework with [fail2ban](https://github.com/fail2ban/fail2ban), which automatically blocks IP addresses that exhibit suspicious behavior, thereby mitigating potential threats.



## Server Access Control

- **Restricted Access**: Access to Kevred servers is strictly limited to authorized personnel. Only designated SSH keys from our team members are allowed for server connections.
- **Monitoring**: We meticulously log and monitor all server access to detect and investigate any unusual activities.

## Validator Key Management

- **Rigorous Access Control**: Access to our validator keys is tightly regulated, restricted solely to essential staff.
- **Key Storage**: Only the identity keypair, required for validator operation, is stored on the server.
- **Multi-factor Authentication**: We enforce multi-factor authentication for all operations that involve validator keys, wherever feasible.

