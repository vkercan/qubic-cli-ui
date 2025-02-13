# Qubic CLI User Interface Proposal

## 1. Goal

Web interface that allows users to execute [Qubic CLI](https://github.com/qubic/qubic-cli) commands (`WALLET`, `BLOCKCHAIN`, `NODE`, `QX`, `QTRY`, `GENERAL`, ...) via the Web interface running in the Cloud or locally using Docker. Current version will not include Qubick wallet integration.

* Cloud version: Will offer execution of commands only were **seed is not required**.
* Local version: running in Docker and will have additional functionality of adding a seed and allow execution of commands where **seed is also required**.

## 2. Scope of work and deliverables

| #   | Activity          | Description                                                                                           | Deliverables                               |
| --- | :---------------- | :---------------------------------------------------------------------------------------------------- | :----------------------------------------- |
| 1   | Analysis, Design  | Review of technical requirements<br>Review of functional requirements<br>Review of UI/UX requirements | Technical specification<br>Functional specification<br>UI/UX design |
| 2   | Engineering       | Development<br>Testing                                                                                | Qubic CLI User Interface                   |
| 3   | Cloud             | Setup of test and production environments<br>Setup of CI/CD pipelines<br>Setup of Monitoring<br>Setup of Analytics          | Deployed Qubic CLI User Interface          |
| 4   | Go Live           | Go Live monitoring and support                                                                        | Live Qubic CLI User Interface              |
| 5   | Local version     | Seed support<br>Docker support<br>Documentation for local installation                                | Locally running Qubic CLI User Interface   |

## 3. Tech stack

* Frontend: Nest.js and React
* Cloud: AWS or GCP

## 4. UI Proposal

> **NOTE:** Not a finished design proposal, but a collection of elements for better visualisation of final product.

![CleanShot 2025-02-11 at 13 45 36@2x](https://github.com/user-attachments/assets/05085beb-744b-4082-8606-90dd2ccf23d4)

## 6. Costs, milestones and payment plan

### 6.1 Costs

| Activity         | Costs        |
| :--------------- | :----------- |
| Analysis, Design | $3,000       |
| Engineering      | $10,000      |
| Cloud            | $4,000       |
| Go Live          | $1,000       |
| Local version    | $3,000       |
| **TOTAL**        | **$21,000**  |

### 6.2 Milestones

| Milestone    | Deliverables                                                            | Deadline   |
| :----------- | :---------------------------------------------------------------------- | :--------- |
|              | Kick-off                                                                | 03.03.2025 |
| Milestone 1  | Technical specification<br>Functional specification<br>UI/UX design     | 31.03.2025 |
| Milestone 2  | Qubic CLI User Interface (Prototype)<br>Test Cloud environment          | 30.04.2025 |
| Milestone 3  | Qubic CLI User Interface (Full version)<br>Production Cloud environment | 30.05.2025 |
| Milestone 4  | Go Live                                                                 | 02.06.2025 |
| Milestone 5  | Local Docker version                                                    | 30.06.2025 |

### 6.3 Payment plan

| Milestone    | Payment plan |
| :----------- | :----------- |
| Milestone 1  | $3,000       |
| Milestone 2  | $7,000       |
| Milestone 3  | $7,000       |
| Milestone 4  | $1,000       |
| Milestone 4  | $3,000       |
| **TOTAL**    | **$21,000**  |

### 6.4 Cloud costs

Estimated $5,000 per year.

## 7. Maintenance and Updates

Quaterly updates that will include:
* compatibility with future updates to the [Qubic CLI](https://github.com/qubic/qubic-cli),
* update of software and infrastructure components to the latest version.

Estimated costs of each quaterly release: $1,000 - $2,000 (depending on the changes).
  
## 7. About Dhimahi

[Dhimahi](https://dhimahi.com/) is a Slovenian software company with headquarters in Ljubljana and offices in Zagreb and Belgrade.

## 8. Summary

This proposal outlines development of a Web interface enabling users to execute [Qubic CLI](https://github.com/qubic/qubic-cli) commands via a cloud-based or Docker-deployed Web interface.

Key points of the proposal:
* **Goal:** Simplify [Qubic CLI](https://github.com/qubic/qubic-cli) command execution through a Web interface.
* **Scope:** Activities include requirement analysis, product design, frontend development, Cloud environment setup, and Go Live support.
* **Tech stack:** Nest.js and React, AWS/GCP for cloud deployment.
* **Milestones:** Four phases covering analysis, design, prototyping, development, deployment, and Go Live.
* **Costs:** $18,000.
* **Developer:** The project will be led by Dhimahi, a Slovenia-based software company with regional offices.
* **Future considerations:** Qubick wallet integration.
