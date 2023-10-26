<p align="center">
    <a href="https://github.com/oceanbase/oceanbase">
        <img alt="OceanBase Logo" src="images/logo.svg" width="50%" />
    </a>
</p>

<p align="center">
    <a href="https://github.com/oceanbase/oceanbase/blob/master/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/license-MulanPubL--2.0-blue" />
    </a>
    <a href="https://github.com/oceanbase/oceanbase/releases/latest">
        <img alt="Release" src="https://img.shields.io/badge/dynamic/json?color=blue&label=release&query=tag_name&url=https%3A%2F%2Fapi.github.com%2Frepos%2Foceanbase%2Foceanbase%2Freleases%2Flatest" />
    </a>
    <a href="https://github.com/oceanbase/oceanbase">
        <img alt="Stars" src="https://img.shields.io/badge/dynamic/json?color=blue&label=stars&query=stargazers_count&url=https%3A%2F%2Fapi.github.com%2Frepos%2Foceanbase%2Foceanbase" />
    </a>
    <a href="https://github.com/oceanbase/oceanbase">
        <img alt="Forks" src="https://img.shields.io/badge/dynamic/json?color=blue&label=forks&query=forks&url=https%3A%2F%2Fapi.github.com%2Frepos%2Foceanbase%2Foceanbase" />
    </a>
    <a href="https://en.oceanbase.com/docs/oceanbase-database">
        <img alt="English Docs" src="https://img.shields.io/badge/docs-English-blue" />
    </a>
    <a href="https://www.oceanbase.com/docs/oceanbase-database-cn">
        <img alt="Chinese Docs" src="https://img.shields.io/badge/文档-简体中文-blue" />
    </a>
    <a href="https://github.com/oceanbase/oceanbase/actions/workflows/compile.yml">
        <img alt="Building Status" src="https://img.shields.io/github/actions/workflow/status/oceanbase/oceanbase/compile.yml?branch=master" />
    </a>
    <a href="https://github.com/oceanbase/oceanbase/commits/master">
        <img alt="Last Commit" src="https://img.shields.io/github/last-commit/oceanbase/oceanbase/master" />
    </a>
    <a href="https://join.slack.com/t/oceanbase/shared_invite/zt-1e25oz3ol-lJ6YNqPHaKwY_mhhioyEuw">
        <img alt="Join Slack" src="https://img.shields.io/badge/Slack-Join%20Oceanbase-brightgreen?logo=slack" />
    </a>
</p>

English | [中文版](README_CN.md)

**OceanBase Database** is a distributed relational database developed by Ant Group. It operates on a common server cluster and provides high availability and linear scalability through the use of the [Paxos protocol](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf) and a distributed architecture.

## Key Features

- **Transparent Scalability**: An OceanBase cluster can be scaled out to 1,500 nodes, handling petabytes of data and a trillion rows of records.

- **Ultra-fast Performance**: OceanBase is the only distributed database that has achieved record-breaking performance, with 707 million TPC-C transactions per minute and 15.26 million TPC-H queries per hour at 30,000GB.

- **Real-time Operational Analytics**: It offers a unified system for both transactional and real-time operational analytics workloads.

- **Continuous Availability**: OceanBase uses the Paxos Consensus algorithm to achieve Zero RPO (Recovery Point Objective) and less than 8 seconds of RTO (Recovery Time Objective). It supports intra-city and remote disaster recovery, ensuring zero data loss.

- **MySQL Compatible**: OceanBase Database is highly compatible with MySQL, requiring minimal or no modifications for migration.

- **Cost Efficiency**: The cutting-edge compression technology saves 70%-90% of storage costs without compromising performance. The multi-tenancy architecture achieves higher resource utilization.

For more details, see [key features](https://en.oceanbase.com/product/opensource).

## Quick Start

### 🔥 Start with All-in-One

You can quickly deploy a standalone OceanBase Database using the following commands. (Linux Only)

```shell
# Download and install the all-in-one package (internet connection is required)
bash -c "$(curl -s https://obbusiness-private.oss-cn-shanghai.aliyuncs.com/download-center/opensource/oceanbase-all-in-one/installer.sh)"
source ~/.oceanbase-all-in-one/bin/env.sh

# Quickly deploy OceanBase Database
obd demo
🐳 Start with Docker
Start an OceanBase Database instance:
shell
Copy code
# Deploy a mini standalone instance.
docker run -p 2881:2881 --name oceanbase-ce -e MINI_MODE=1 -d oceanbase/oceanbase-ce
Connect to the OceanBase Database instance:
shell
Copy code
docker exec -it oceanbase-ce ob-mysql sys # Connect to the root user of the sys tenant.
For more details, see Quick experience or Quick Start (Simplified Chinese).

👨‍💻 Start Developing
Refer to the OceanBase Developer Document to learn how to compile and deploy a manually compiled observer.

Roadmap
For future plans, check out the Roadmap 2023. You can also explore the OceanBase Roadmap for more details.

Case Study
OceanBase has helped over 400 customers upgrade their databases in various industries, including Financial Services, Telecom, Retail, Internet, and more.

For more information, see success stories and Who is using OceanBase.

System Architecture
Learn about the system architecture.

Contributing
We highly appreciate contributions. Get started by reading the development guide.

License
OceanBase Database is licensed under the Mulan Public License, Version 2. Refer to the LICENSE file for more information.

Community
Join the OceanBase community via:

Slack Workspace
Chinese User Forum
DingTalk Group: 33254054 (QR code)
WeChat Group (Add the assistant with WeChat ID: OBCE666).
