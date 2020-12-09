# Service Level Agreement OpenProject Enterprise Cloud

This SLA amends the Agreement between [OpenProject](https://www.openproject.org/legal/imprint) and Customer and addresses the uptime guarantees in relation to the Services [OpenProject Enterprise Cloud](https://www.openproject.org/hosting/) we provide to you and your remedies for our failure to meet such guarantees. The remedies contained in this SLA are your sole and exclusive remedies for any issues addressed herein. We may update this SLA from time to time in our sole discretion; the current version may be found at https://www.openproject.org/legal/sla/.

## 1. Service availability

### 1.1 Availability 

OpenProject GmbH will make the Services available 99.9% of the time, excluding any *Excused Downtime*. In a given calendar month, we calculate “Service Availability” as follows:

**Service Availability = total minutes Services are available x 100 / (total minutes in the month – Excused Downtime)**

### 1.1 Excused downtime

“*Excused Downtime*” means the length of time the Services are unavailable due to:

1. Scheduled Maintenance;
2. Emergency Maintenance;
3. Beta Services;
4. Force Majeure events; and
5. the actions or omissions of you, your Authorized Users, or any third-party acting on your behalf or at your direction, including any unauthorized use of the Services, breach of the Agreement or Acceptable Use Policy, or any use or configuration of the Services that exceeds OpenProject's recommendations or advertised limits.

### 1.2 Schedule maintenance

“*Scheduled Maintenance*” includes any maintenance performed during the following windows or for which we provide reasonable notice or coordination with you in advance of the maintenance.

| **Data Center location:** | **Maintenance window:** |
| ------------------------- | ----------------------- |
| European Union            | 6:00 am - 08:00 am CET  |

“*Emergency Maintenance*” means any maintenance performed outside the Scheduled Maintenance windows without advance notice where such maintenance is reasonably and urgently required to protect the integrity, availability, or security of any online systems.

### 1.2 SLA credits

You are entitled to a credit of 5% of the applicable monthly Fees for each full hour of downtime in excess of the Service Availability targets. (For example, you will receive a 5% credit for between 1 and 60 minutes of downtime in excess of the Service Availability targets, a 10% credit for between 61 and 120 minutes, etc.) In order to receive a credit, you must contact Support within 30 days of the event giving rise to the credit. Credits are based on our monitoring, shall not exceed 100% of the applicable monthly Fees, may not be carried over or aggregated, are forfeited at the expiration or termination of the Agreement, and will not be paid or provided as a refund.

## 2. Backup

Automated Amazon Relational Database Service (RDS) backups are generated daily and retained for 30 days to allow for point-in-time data restoration. Snapshots of the primary RDS are also taken daily. Copies of the snapshot are sent to a secondary region, where they’re kept for 3 days before being deleted. RDS snapshots are encrypted at rest. 

OpenProject Enterprise Cloud does not support the use of backup data to roll back changes.

## 3. Software updates

We install the latest versions of the OpenProject software to deploy the latest software updates of the stable release branch.

> Todo: Desrciption of the other parts like (operating system, web server, database)

## 4. Acceptable use policy

You may not interfere with our business or our ability to provide services to other customers, nor take any action nor make any use of the Services that places excessive burdens on the network or systems used to provide such services. Specifically, you may not use the service for use cases other than project management, team collaboration, product management and product lifecycle management. If your use of the Services materially exceeds the use by similarly situated customers, we may offer to move you to a different plan or charge you for the additional use. If you refuse, we may place restrictions on your use of the Services. You may not perform any vulnerability or penetration testing of OpenProject’s network or systems without our prior written approval.

## 5. Support service level 

 OpenProject provides its services at different support levels defined as follows:

| Support service levels                   | Professional Support     | Premier Support          | Corporate Support        |
| ---------------------------------------- | ------------------------ | ------------------------ | ------------------------ |
| Service hours                            | Mon-Fri, 09:30-17:30 CET | Mon-Fri, 09:30-17:30 CET | Mon-Fri, 09:00-18:00 CET |
| Response time – critical incidents       | 8 h                      | 6 h                      | 2 h                      |
| Response time – major incidents          | best effort              | 12 h                     | 6 h                      |
| Response time – minor incidents          | best effort              | 48 h                     | 24 h                     |
| Scheduled standby and upgrade assistance | -                        | included                 | included                 |
| Priority development and escalation      | -                        | included                 | included                 |

## 5. Support communication channel 

 OpenProject provides its support services with different communication channels as follows: 

| Support service levels     | Professional Support | Premier Support | Corporate Support |
| -------------------------- | -------------------- | --------------- | ----------------- |
| Ticket                     | -                    | included        | included          |
| Email                      | included             | included        | included          |
| Phone                      | -                    | included        | included          |
| Remote login/remote hands  |                      | included        | included          |
| Dedicated support engineer |                      |                 | included          |
| Named support contacts     | 1                    | 3               | 8                 |
