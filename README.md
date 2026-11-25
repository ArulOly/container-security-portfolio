
# Container Security Portfolio

Practical Container Security, Secure Infrastructure Deployment and System Administration

## 1. Portfolio Overview

This repository documents my practical development in container security, Docker infrastructure, secure system administration and containerised service deployment.

The portfolio consists of ten structured laboratory projects covering foundational, intermediate and intermediate-advanced container security concepts within controlled local environments.

Each project focuses on specific technical competencies, defensive security configurations, infrastructure management procedures and operational verification methods.

The portfolio demonstrates progressive technical development through structured practical exercises, independent experimentation and technical documentation.

This repository represents a completed milestone in my container security education and professional development.

## 2. Portfolio Objectives

- Develop practical container security competencies.
- Implement secure multi-container infrastructure.
- Apply defence-in-depth security principles.
- Configure container resource restrictions.
- Implement network segmentation and service isolation.
- Apply Linux container security hardening.
- Configure persistent database storage.
- Perform database backup and disaster recovery.
- Implement container health monitoring.
- Conduct container image vulnerability assessments.
- Apply advanced container runtime security controls.
- Implement secure credential and secrets management.
- Develop infrastructure troubleshooting skills.
- Produce structured professional technical documentation.
- Establish a foundation for cybersecurity and infrastructure administration.

## 3. Portfolio Status

| Parameter | Status |
|---|---|
| Portfolio Status | Completed |
| Total Projects | 10 |
| Completed Projects | 10 |
| Remaining Projects | 0 |
| Completion | 100% |
| Technical Level | Foundational to Intermediate-Advanced |
| Primary Technology | Docker |
| Infrastructure Management | Docker Compose |
| Security Focus | Defensive Container Security |
| Environment | Controlled Local Laboratory |
| Development Approach | Structured Practical Learning |
| Project Scope | Finalised |
| Additional Projects | Not Planned |

This portfolio represents a completed collection of ten container security projects.

The repository is maintained as a permanent record of practical learning, technical development and container security competencies.

## 4. Project Directory

| Project | Project Title | Technical Focus | Status |
|---|---|---|---|
| 01 | Secure Multi-Container Deployment | Secure infrastructure deployment | Completed |
| 02 | Container Resource Management | CPU and memory restrictions | Completed |
| 03 | Container Network Segmentation | Network isolation and controlled communication | Completed |
| 04 | Container Security Hardening | Linux capabilities and privilege restrictions | Completed |
| 05 | Persistent Storage and Data Integrity | Docker volumes and database persistence | Completed |
| 06 | Database Backup and Disaster Recovery | Physical backups and database restoration | Completed |
| 07 | Container Health Monitoring | Health checks and service dependencies | Completed |
| 08 | Container Vulnerability Assessment | Image scanning, CVE analysis and SBOM | Completed |
| 09 | Advanced Container Runtime Hardening | Non-root execution and filesystem protection | Completed |
| 10 | Secure Container Secrets Management | Credential protection and internal networking | Completed |

## 5. Repository Structure

```text
container-security-portfolio/
|
|-- 01-secure-container-deployment/
|-- 02-container-resource-management/
|-- 03-network-segmentation/
|-- 04-container-hardening/
|-- 05-persistent-storage/
|-- 06-disaster-recovery/
|-- 07-container-health-monitoring/
|-- 08-container-vulnerability-assessment/
|-- 09-advanced-container-hardening/
|-- 10-secure-secrets-management/
|
|-- README.md
```

Each project contains individual technical documentation describing its objectives, infrastructure configuration, security controls, verification procedures and learning outcomes.

The repository is organised according to technical progression and individual security competencies.

## 6. Project Summaries

### Project 01 - Secure Multi-Container Deployment

Campus Helpdesk System

This project focuses on secure deployment of Apache HTTPD and PostgreSQL using Docker Compose.

Technical areas:

- Multi-container deployment
- Docker Compose configuration
- Web and database service configuration
- Network segmentation
- Database port isolation
- Persistent storage
- Container security configuration
- Infrastructure verification

### Project 02 - Container Resource Management

Campus Equipment Booking System

This project focuses on container resource allocation, infrastructure resource governance and operational stability.

Technical areas:

- CPU restrictions
- Memory restrictions
- Container resource monitoring
- Resource configuration verification
- Service restart policies
- Infrastructure stability
- Resource consumption management

### Project 03 - Container Network Segmentation

Campus Event Registration System

This project focuses on controlled container communication and separation of frontend and backend infrastructure.

Technical areas:

- Custom Docker bridge networks
- Frontend and backend segmentation
- Container DNS resolution
- Database network isolation
- Network membership verification
- Controlled service exposure
- Internal container communication

### Project 04 - Container Security Hardening

Campus Student Services System

This project focuses on reducing container privileges and implementing defensive runtime security controls.

Technical areas:

- Linux capability restrictions
- Privileged mode restrictions
- Prevention of additional privilege acquisition
- Least-privilege configuration
- Container security inspection
- Attack surface reduction
- Runtime configuration verification

### Project 05 - Persistent Storage and Data Integrity

Campus Library Loan System

This project focuses on persistent database storage and preservation of data across container lifecycle operations.

Technical areas:

- Docker named volumes
- PostgreSQL persistent storage
- Database record verification
- Container recreation
- Data integrity verification
- Volume lifecycle management
- Volume backup and restoration

### Project 06 - Database Backup and Disaster Recovery

Campus Facility Maintenance System

This project focuses on physical database volume backups, restoration procedures and operational recovery.

Technical areas:

- PostgreSQL shutdown procedures
- Physical volume archives
- Backup verification
- Separate restoration volumes
- Database recovery
- Recovered record verification
- Original volume preservation
- Operational resilience

### Project 07 - Container Health Monitoring and Secure Deployment

Campus IT Asset Inventory System

This project focuses on service readiness, container health monitoring and infrastructure reliability.

Technical areas:

- PostgreSQL health checks
- Health-based service dependencies
- Container health inspection
- Database readiness monitoring
- Service availability
- Operational resilience
- Container lifecycle monitoring
- Secure infrastructure deployment

### Project 08 - Container Vulnerability Assessment and Image Security

Container Image Security Assessment Environment

This project focuses on defensive container image vulnerability assessment and software supply chain security.

Technical areas:

- Docker Scout
- Container image vulnerability scanning
- Common Vulnerabilities and Exposures
- Common Vulnerability Scoring System
- Vulnerability severity classification
- Software bill of materials
- Software dependency identification
- Image remediation assessment
- Security report generation

### Project 09 - Advanced Container Runtime Hardening

Secure Internal Web Service Environment

This project focuses on advanced runtime restrictions and reducing container attack surfaces.

Technical areas:

- Non-root container execution
- Read-only root filesystems
- Temporary filesystem configuration
- Linux capability restrictions
- Process creation limits
- Localhost port binding
- Filesystem write restrictions
- Runtime security verification
- Container health monitoring

### Project 10 - Secure Container Secrets and Credential Management

Secure Campus Records Infrastructure

This project focuses on protecting sensitive credentials and separating secrets from infrastructure configuration.

Technical areas:

- Docker Compose secrets
- PostgreSQL password file integration
- Service-specific secret access
- Internal Docker networks
- Sensitive file repository exclusion
- Database authentication verification
- Credential lifecycle management
- Credential rotation awareness
- Secure infrastructure configuration

## 7. Technical Progression

| Development Level | Projects | Primary Competencies |
|---|---|---|
| Foundational | 01 - 03 | Deployment, resource management and networking |
| Intermediate | 04 - 07 | Hardening, persistence, recovery and health monitoring |
| Intermediate-Advanced | 08 - 10 | Vulnerability assessment, runtime protection and secrets management |

The portfolio follows a progressive learning approach, beginning with essential container infrastructure concepts and extending into more specialised defensive security configurations.

Foundational projects establish essential deployment and infrastructure management knowledge.

Intermediate projects introduce defensive security controls, data protection and infrastructure reliability.

Intermediate-advanced projects introduce software supply chain security, advanced runtime restrictions and secure credential management.

The development levels represent the relative complexity of the laboratory exercises rather than formal professional certifications.

## 8. Technologies and Tools

| Technology | Application |
|---|---|
| Docker | Container deployment and management |
| Docker Compose | Multi-container infrastructure configuration |
| Apache HTTPD | Containerised web services |
| NGINX | Unprivileged web service deployment |
| PostgreSQL | Relational database infrastructure |
| Docker Scout | Container image vulnerability assessment |
| Alpine Linux | Temporary utility containers |
| Linux | Container runtime and security concepts |
| PowerShell | Deployment and verification operations |
| YAML | Infrastructure configuration |
| SQL | Database creation and verification |
| Git | Version control |
| GitHub | Technical documentation and portfolio management |
| Markdown | Structured technical documentation |

## 9. Container Infrastructure Architecture

The foundational multi-container projects use a segmented infrastructure architecture consisting of a web service, database service, custom Docker networks and persistent storage.

```text
Local Host
    |
Published Web Port
    |
Web Container
    |
    |-- Frontend Network
    |
    |-- Backend Network
            |
       PostgreSQL Container
            |
       Named Docker Volume
            |
       Backup and Recovery
```

The database service is not directly published to the host network.

Custom Docker networks provide controlled network membership and separation between infrastructure components.

Named Docker volumes provide persistent database storage independently of the container lifecycle.

Later projects extend these infrastructure concepts through health monitoring, advanced runtime restrictions, vulnerability assessment and service-specific secrets management.

Individual project architectures vary according to their technical objectives.

The architecture represents a laboratory infrastructure model rather than a complete production application architecture.

## 10. Security Controls

| Security Control | Purpose |
|---|---|
| Network segmentation | Restrict unnecessary container communication |
| Database port isolation | Reduce direct database exposure |
| CPU restrictions | Control processor resource consumption |
| Memory restrictions | Control memory resource consumption |
| Restart policies | Support service lifecycle management |
| Privileged mode restrictions | Avoid privileged container execution |
| Linux capability restrictions | Remove unnecessary operating system privileges |
| no-new-privileges | Prevent additional privilege acquisition |
| Named Docker volumes | Maintain persistent application data |
| Physical volume backups | Support database recovery |
| Separate restoration volumes | Protect original database storage during recovery |
| Health checks | Monitor service readiness |
| Health-based dependencies | Coordinate initial service startup |
| Image vulnerability scanning | Identify known image vulnerabilities |
| SBOM generation | Improve software dependency visibility |
| Non-root execution | Reduce runtime privileges |
| Read-only root filesystems | Restrict filesystem modification |
| Temporary filesystem restrictions | Limit temporary storage permissions |
| Process limits | Restrict container process creation |
| Localhost port binding | Reduce direct external service exposure |
| File-based secrets | Separate credentials from infrastructure configuration |
| Internal Docker networks | Restrict external network connectivity |
| Repository exclusion rules | Reduce accidental sensitive file publication |

Security controls are documented according to the requirements and technical scope of each individual project.

These controls contribute to defensive infrastructure security but do not independently guarantee complete protection.

## 11. Security Principles

The portfolio incorporates the following defensive security principles:

- Defence in depth
- Least privilege
- Attack surface reduction
- Network segmentation
- Service isolation
- Resource governance
- Data confidentiality
- Data integrity
- Data availability
- Secure configuration management
- Infrastructure resilience
- Software supply chain security
- Vulnerability management
- Secure credential management
- Operational visibility
- Security verification
- Risk-based remediation

These principles provide a foundation for secure containerised infrastructure and broader cybersecurity practices.

## 12. Infrastructure Deployment and Verification

The portfolio incorporates practical deployment and verification procedures using Docker command-line tools.

Common deployment and inspection commands include:

```powershell
docker version
docker info
docker compose config --quiet
docker compose up -d
docker compose ps
docker ps
docker stats --no-stream
docker network ls
docker volume ls
docker image ls
```

Additional project-specific verification procedures include:

- Container configuration inspection
- CPU and memory restriction verification
- Network membership inspection
- Container DNS resolution verification
- Database readiness verification
- Persistent volume inspection
- Database record verification
- Backup archive inspection
- Container health status monitoring
- Linux capability inspection
- Filesystem permission verification
- Non-root execution verification
- Secret mount verification
- Database authentication verification
- Container image vulnerability assessment

Verification procedures are documented within the relevant individual project.

Expected verification results describe the intended behaviour of each configuration and are distinguished from observed runtime evidence.

## 13. Vulnerability Management and Software Supply Chain Security

Container image security forms an important component of defensive infrastructure management.

The portfolio introduces vulnerability assessment using Docker Scout to identify known security issues within container images.

Assessment areas include:

- Container image identification
- Image metadata inspection
- Image digest identification
- Software dependency identification
- CVE identification
- Vulnerability severity assessment
- Available remediation analysis
- Software bill of materials generation
- Security assessment reporting

Vulnerability assessment supports informed image selection and risk-based remediation decisions.

Vulnerability findings may change as container images and vulnerability databases are updated.

Vulnerability scanning identifies known security issues but does not guarantee that an image is completely secure.

## 14. Data Protection and Disaster Recovery

Persistent storage and recovery procedures are incorporated into the portfolio to demonstrate database availability and data integrity concepts.

Technical areas include:

- Named Docker volume configuration
- Database persistence across container recreation
- Database shutdown before physical backup
- Physical database volume archives
- Backup archive verification
- Restoration into separate volumes
- Database readiness verification
- Recovered database record verification
- Original volume preservation
- Secure backup management

The recovery approach separates the original database volume from the restored volume to reduce unnecessary risk to the original data.

Recovery verification focuses on confirming database availability and preservation of the original database records.

The recovery procedures demonstrate local laboratory recovery techniques rather than a complete enterprise disaster recovery strategy.

## 15. Credential Protection and Repository Security

Sensitive information must remain separate from publicly accessible technical documentation.

Repository security practices include:

- Avoiding hardcoded database passwords
- Using environment variable references
- Using file-based Docker Compose secrets
- Restricting secret access to required services
- Excluding local credential files from version control
- Excluding database backup archives
- Avoiding publication of sensitive configuration information
- Reviewing repository contents before committing changes
- Maintaining awareness of credential rotation procedures

Actual passwords, authentication tokens, private keys and confidential information must not be published in this repository.

Standalone Docker Compose secrets provide local file-based credential separation but do not replace dedicated enterprise secrets management platforms.

## 16. Technical Competencies

| Competency Area | Practical Coverage |
|---|---|
| Container Deployment | Docker and Docker Compose |
| Infrastructure Configuration | YAML-based service definitions |
| Resource Management | CPU, memory and process restrictions |
| Container Networking | Custom bridge networks and internal networks |
| Linux Security | Capabilities and privilege management |
| Runtime Hardening | Non-root execution and read-only filesystems |
| Database Administration | PostgreSQL deployment and verification |
| Storage Management | Docker named volumes |
| Disaster Recovery | Physical backups and volume restoration |
| Infrastructure Monitoring | Container health checks |
| Service Reliability | Health-based startup dependencies |
| Vulnerability Management | Docker Scout and CVE assessment |
| Software Supply Chain Security | SBOM and image assessment |
| Credential Management | File-based secrets and authentication |
| Version Control | Git and GitHub |
| Technical Documentation | Structured Markdown documentation |
| Infrastructure Troubleshooting | Container inspection and logging |

## 17. Learning Outcomes

The portfolio supports practical development in the following areas:

- Secure container infrastructure deployment
- Multi-container service configuration
- Docker resource governance
- Container network architecture
- Linux container security
- Least-privilege implementation
- Persistent database storage
- Database backup and recovery
- Data integrity verification
- Infrastructure health monitoring
- Service dependency management
- Container image vulnerability assessment
- Software supply chain security
- Advanced runtime hardening
- Secure credential management
- Infrastructure troubleshooting
- Technical documentation
- Version control
- Independent technical learning

The portfolio provides a foundation for broader technical development in cybersecurity, infrastructure security, cloud technologies and secure system administration.

## 18. Portfolio Completion

This portfolio concludes with ten structured container security projects.

| Completion Category | Result |
|---|---|
| Foundational Projects | 3 of 3 |
| Intermediate Projects | 4 of 4 |
| Intermediate-Advanced Projects | 3 of 3 |
| Total Completed Projects | 10 of 10 |
| Remaining Projects | 0 |
| Overall Completion | 100% |
| Portfolio Status | Completed |

The completed collection covers secure infrastructure deployment, resource management, network segmentation, container hardening, persistent storage, disaster recovery, health monitoring, vulnerability assessment and credential protection.

The portfolio represents a completed milestone in my technical development within container security and secure infrastructure administration.

The scope of this repository is finalised, with no additional projects planned.

## 19. Portfolio Scope and Professional Development

This portfolio is maintained as a completed practical learning and professional development repository.

Projects 01 to 06 are adapted from related container security practical exercises and intentionally share common infrastructure patterns to reinforce foundational security competencies.

Projects 07 to 10 extend these concepts through independent laboratory exercises covering infrastructure monitoring, vulnerability assessment, advanced runtime hardening and secure credential management.

The campus system scenarios represent simulated infrastructure environments rather than complete production applications.

All projects are intended for defensive security education, authorised experimentation and controlled local laboratory use.

The configurations are not presented as production-certified infrastructure or guarantees of complete security.

The portfolio reflects practical educational development and does not claim professional certifications, enterprise deployment experience or formal security accreditation.

This repository serves as a permanent record of my container security learning, technical documentation and practical infrastructure development.

The completion of this portfolio establishes a foundation for broader professional development in cybersecurity, cloud security, infrastructure management and secure system administration.

## 20. Final Portfolio Statement

Portfolio Name: Container Security Portfolio

Portfolio Category: Defensive Cybersecurity and Infrastructure Security

Portfolio Status: Completed

Total Projects: 10

Completion: 100%

Technical Scope: Foundational to Intermediate-Advanced

Environment: Controlled Local Laboratory

Repository Scope: Finalised

This portfolio represents the completion of a structured collection of container security projects and documents an important milestone in my technical education and professional development.

---

Container Security Portfolio

Practical Learning | Defensive Security | Secure Infrastructure | Professional Development

