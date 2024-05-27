
# RedTeamTooling

This repository contains a collection of tools and scripts written in Rust for offensive security and red team operations. These tools are designed to assist penetration testers, security researchers, and red teamers in various tasks during engagements or security assessments.

## Tools

### Botnet

A botnet implementation in Rust for creating and controlling a network of compromised systems.

### Command Execution

A Rust-based tool for executing commands on remote systems, supporting various techniques like named pipes, scheduled tasks, and more.

### Convert Bytes to SID String

A Rust utility to convert byte arrays to their corresponding Security Identifier (SID) string representation.

### Decode UAC

A Rust tool for decoding User Account Control (UAC) settings and restrictions on a Windows system.

### Get-ASREPROastable

A Rust script to identify Kerberos accounts that are vulnerable to the AS-REP Roasting attack.

### Get-KerbeROASTAble

A Rust tool for identifying Kerberos accounts with readable Service Principal Names (SPNs), which are susceptible to Kerberoasting attacks.

### Get-Unconstrained

A Rust script to identify users with unconstrained delegation privileges, potentially leading to privilege escalation.

### Get-UsersDescription

A Rust utility to retrieve the description field for user accounts, which may contain valuable information.

### Reverse Shell

A collection of reverse shell payloads and listeners written in Rust for establishing remote access.

### Useful Snippets

A collection of small, reusable Rust code snippets for common offensive security tasks.

## Usage

Each tool or script has its own set of instructions and options, which can be accessed by running the tool with the `--help` flag. For example:

```
 Select a folder and run then compile it with rust compiler using rust.c
```

## Contributing

Contributions to this repository are welcome! If you find any issues or have ideas for new tools or improvements, please open an issue or submit a pull request.

## Disclaimer

These tools are provided for educational and research purposes only. They should be used only on systems or networks where you have explicit permission to perform security assessments. Any unauthorized or unlawful use is strictly prohibited.
