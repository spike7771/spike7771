# Standard Operating Procedure: Web App Testing Server Deployment
<br> [MITT] <br/>
<br> [130 Henlow Bay, Winnipeg, MB R3Y 1G4] <br/>
<br> [Phone: +(204) 955 8921] <br/>
<br> Revision Info: Version: 1.0 <br/>
<br> Last Updated: 2026-03-27 <br/>
 <br><br/>
## PURPOSE OF THE DOCUMENT
_This SOP is designed to provide a standardized process for rapidly deploying Linux-based web application test servers in a virtualized environment. Its primary objective is to eliminate false positive bugs caused by variations in test environments by standardizing the configuration of operating system versions, core toolchains, and security policies._
 <br><br/>
## AUDIENCE


## Approved Table:
| Role         | Name       | Signature | Date       |
| :------------ | :--------- | :-------- | :--------- |
| IT Manager    | Qianyi Wen |  Signed   | 2026-03-27 |
| QA Engineer   | Spike 1    |  Signed   | 2026-03-27 |
| DevOps Expert | Spike 2    |  Signed   | 2026-03-27 |
| Project Lead  | Spike 3    |  Signed   | 2026-03-27 |

## SCOPE/OBJECTIVES
This document aims to establish clear boundaries for the setup of test environments to ensure focused and efficient operations:
- __Applicable Audience__: This document applies only to the QA testing department and the operations team responsible for maintaining the lab environment.
- __Scope__: Limited to the setup of internal functional testing, integration testing, and security scanning environments.
- __Scope Limitations__: This document does not cover production environment deployments.
  
    1.  Only virtualization platforms based on the x86_64 architecture are supported.
    2.  Limited to the Ubuntu 22.04 LTS release; other Linux distributions are not covered.

Only the Ubuntu 22.04 LTS release is supported; other Linux distributions are not covered.
## ACCOUNTABILITY MATRIX
| Task / Phase | QA Engineer | IT Manager | DevOps Expert | Project Lead |
| :------------ | :--------- | :-------- | :--------- | :--------- |
|Step 1: Virtual Machine Resource Configuration | Responsible | Accountable| Consulted | Informed|
|Step 2: System Initialization and Update | Responsible | Accountable| Informed | Informed|
|Step 3: Installing the Software Stack and Toolchain | Responsible | Accountable| Consulted | Informed|
|Step 4: Security Hardening and UFW Configuration | Responsible | Accountable| Consulted | Informed|
|Step 5: Environment Verification and Snapshot Creation | Responsible | Accountable| Informed | Consulted|
#### Role Definitions:

- __Responsible__: The person who performs the task. Responsible for the actual execution of specific tasks.

- __Accountable__: The person with final approval authority. Ensures that tasks are completed according to standards.

- __Consulted__: The expert who provides key technical knowledge.

- __Informed__: Members who need to be kept informed of progress and results.

## EXECUTION STEPS
## REVISION HISTORY
