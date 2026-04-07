## Objective
Build an Active Directory home lab using Windows Server and a domain-joined Windows client to practice domain setup, DNS configuration, user administration, group management, and domain authentication.

## Lab Environment
- Windows Server 2025
- Windows client VM
- VirtualBox
- Domain: `terrylab.local`

## What I Built
- Installed Active Directory Domain Services
- Configured DNS for the domain
- Created the `terrylab.local` domain
- Created Organizational Units for lab organization
- Created test domain users
- Created security groups
- Joined a Windows client to the domain
- Logged in successfully with a domain user account

## Organizational Units
- Lab Users
- IT
- Security

## Domain Users
- `analyst1`
- `helpdesk1`
- `tlewis`

## Security Groups
- `IT Support`
- `Security Analysts`

## Key Configuration
### Domain Controller
- Hostname: `WIN-LP2H1C6RF94`
- IP Address: `192.168.56.10`

### Windows Client
- IP Address: `192.168.56.20`
- DNS Server: `192.168.56.10`

## Skills Demonstrated
- Active Directory Domain Services
- DNS configuration
- Domain Controller setup
- OU creation
- User and group administration
- Domain join configuration
- Domain authentication troubleshooting

## Challenges Encountered
During setup, I had to troubleshoot:
- VirtualBox network configuration
- DNS setup and role installation
- DNS host record creation
- AD-integrated DNS zone configuration
- Domain join failures caused by missing AD DNS records

## Outcome
Successfully built a working Active Directory home lab with a functional domain controller, DNS, domain users, security groups, and a domain-joined Windows client authenticated with domain credentials.

## Screenshots
### Active Directory Users and Computers
![AD Users and Computers](https://github.com/Tl39455/active-directory-home-lab/blob/c5647f90d915da0a3ff0facb8bc7671ad2447311/created-ous.png)

### DNS Manager
![DNS Manager](https://github.com/Tl39455/active-directory-home-lab/blob/b3325479c7e2c190da740a7c8e99d9b35abce690/dns-manager-intergrated-zone-ad.png)

### Domain Users
![Domain Users](https://github.com/Tl39455/active-directory-home-lab/blob/06f4293275dd29c0518e14dabc0d24ebc4b6f88a/lab-users.png)

### Security Groups
![Security Groups](screenshots/security-groups.png)

### Domain Authentication
![Domain Authentication](screenshots/domain-authentication.png)
