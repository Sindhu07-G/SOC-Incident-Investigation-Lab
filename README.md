# SOC Incident Investigation Lab

## Project Overview

This project demonstrates a basic Security Operations Center (SOC) investigation workflow in a controlled virtual lab environment.

The objective was to simulate unauthorized SSH login attempts from a Kali Linux system against an Ubuntu Linux target machine, investigate authentication logs, identify the source IP address, and document findings in an incident report.

## Tools Used

* Kali Linux
* Ubuntu Linux
* VirtualBox
* OpenSSH
* Linux Authentication Logs (auth.log)

## Lab Objectives

* Simulate failed SSH login attempts.
* Generate security events for analysis.
* Investigate Linux authentication logs.
* Identify attacker source IP address.
* Analyze authentication failures.
* Create an incident report with findings and recommendations.

## Activities Performed

### 1. SSH Service Verification

Verified that the SSH service was running on the Ubuntu target system.

### 2. Failed Login Simulation

Generated multiple failed SSH login attempts using an invalid username from the Kali Linux machine.

### 3. Log Analysis

Reviewed authentication logs located in:

/var/log/auth.log

Identified:

* Failed password attempts
* Invalid user activity
* Source IP address information
* SSH authentication events

### 4. Incident Investigation

Analyzed security events and documented:

* Source IP Address
* Username used during attack attempts
* Authentication failure details
* Potential security impact

### 5. Incident Reporting

Created a basic incident report summarizing findings and security recommendations.

## Findings

* Multiple failed SSH login attempts detected.
* Invalid username used during authentication attempts.
* Source IP successfully identified.
* No successful compromise occurred.

## Recommendations

* Enable SSH key-based authentication.
* Disable password-based authentication.
* Implement Fail2Ban.
* Monitor authentication logs regularly.
* Restrict SSH access where possible.

## Screenshots

Screenshots demonstrating each stage of the investigation are included in the Screenshots folder.

## Skills Demonstrated

* Security Monitoring
* Log Analysis
* Incident Investigation
* Linux Administration
* SSH Security
* Cybersecurity Documentation
* SOC Analyst Fundamentals

