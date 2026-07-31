<h1 align="left">Nirmal Chhodvadiya</h1>

<p align="left">
<b>Senior AWS Data Engineer</b> · AWS Glue SME · Community organiser in Surat<br/>
I build data platforms on AWS, and I spend a lot of my time explaining them to other people.
</p>

<p align="left">
<a href="https://nirmalchhodvadiya.in"><img src="https://img.shields.io/badge/portfolio-nirmalchhodvadiya.in-FF9900?style=flat-square&labelColor=232F3E" /></a>
<a href="https://linkedin.com/in/nirmalchhodvadiya"><img src="https://img.shields.io/badge/linkedin-nirmalchhodvadiya-0A66C2?style=flat-square&labelColor=232F3E" /></a>
<a href="https://youtube.com/@nirmalpatel008"><img src="https://img.shields.io/badge/youtube-@nirmalpatel008-FF0000?style=flat-square&labelColor=232F3E" /></a>
<a href="https://linktr.ee/nmchhodvadiya008"><img src="https://img.shields.io/badge/links-linktree-43E55E?style=flat-square&labelColor=232F3E" /></a>
<a href="mailto:nmchhodvadiya008@gmail.com"><img src="https://img.shields.io/badge/email-say_hello-D14836?style=flat-square&labelColor=232F3E" /></a>
</p>

---

## Current state

```console
$ aws profile describe --user nirmal

ROLE        Senior AWS Data Engineer, 6+ years
DEPTH       AWS Glue Subject-Matter Expert (AWS India Big Data, 2021-2024)
BUILT       Production data lake + CDC platform at Credibly, CloudFormation only
COMMUNITY   Organiser, AWS User Group Surat  ·  AWS Community Builder since 2021
STAGE       AWS Summit Bengaluru speaker, 2025 and 2026
BASE        Surat, India  ·  remote-first  ·  IST, happy to stretch either way

STATUS      open to new work
LOOKING AT  Developer Advocacy / DevRel
            Cloud Solutions Architect (Data & Analytics)
            Data & Analytics presales / solutions engineering
            Technical content, enablement, developer education
```

---

## Two halves of the same job

I do not think of the engineering and the community work as separate tracks. One feeds the other. The talks are good because the systems were real, and the systems got better because I had to explain them to strangers.

<table>
<tr><td width="50%" valign="top">

### What I build

Production data platforms where the hard part is never the happy path.

Nanosecond-precision timestamps that break naive dedup. Schema evolution across deeply nested DynamoDB JSON. Primary-key consistency when the source system does not cooperate. A wildcard-versus-explicit overlap between two CDC tasks that quietly duplicated 137 tables until I injected 122 exclude rules programmatically.

I stood up an entire production AWS account through CloudFormation only, no console changes, across eight-plus stacks. Enterprise naming convention, parameterised per environment, no drift.

</td><td width="50%" valign="top">

### How I show up

Meetups, workshops, conference stages, YouTube, written docs.

I have delivered Bedrock, MCP and Serverless workshops to rooms of 77 to 90 builders. Guest sessions opened to 500-plus students. Five-plus internal enablement sessions on Glue and PySpark to engineers inside AWS, some of them more senior than me.

My demos come out of systems I actually ran, which is the only reason the questions afterwards are answerable.

</td></tr>
</table>

---

## Speaking

Full history at [nirmalchhodvadiya.in/#speaking](https://nirmalchhodvadiya.in/#speaking)

**AWS Summit Bengaluru 2026** · Conference speaker
Building near real-time data pipelines with AWS DMS, Aurora to Aurora, full load plus CDC. Dual-target endpoint design, latency versus catalog-churn tradeoffs, running DMS at production scale.
[Watch](https://youtu.be/lh3vMIL85T4)

**AWS Summit Bengaluru 2025** · Developer Lounge
From meetup attendee to AWS engineer. The seven-year version of how community shaped my cloud career.
[Watch](https://youtu.be/YDKte_7OkqE)

**AWS Community Day Vadodara 2025** · 600+ attendees
From data chaos to insights. A practical Aurora Zero-ETL and CDC deep dive.

**AWS Community Day Ahmedabad 2025**
Near real-time data pipelines, plus a "Listen to Expert" guest session for the Ahmedabad community.

**AWS Cloud Club PPSU** · Feb 2026
Cloud fundamentals, IaaS/PaaS/SaaS, certification pathways. Opened to 500+ students online.

---

## Community

I am one of the organisers of **AWS User Group Surat**. I want to be precise about that, because community numbers get claimed too easily.

The group existed before I joined it. I first walked in as an attendee, before I had a job in cloud. Years later I ended up helping run it, alongside co-organisers and a volunteer crew who do the logistics, the venue chasing, the registration desk, and the thousand unglamorous things that make an event happen. Every speaker who has said yes to us is part of it too.

Where the community is today:

| | |
| :--- | :--- |
| Meetup members | 3,350+ |
| LinkedIn followers | 1,000+ |
| Cadence | monthly, averaging 70 to 80 attendees |
| re:Invent 2025 Recap | 114 registrations |
| AI for Bharat, Bedrock workshop | 90+ builders |
| MCP workshop | 83 attendees |
| Serverless workshop | 77 attendees |
| Coming up | **AWS Community Day Surat, October 2026**, our first |

My share of that is showing up consistently, running sessions, and helping keep the cadence going. The number belongs to everyone who turned up.

Also an **AWS Community Builder** since 2021, Networking and Content Delivery cohort.

---

## Writing and video

- **AWS Knowledge Center**, public article on troubleshooting the `Unable to execute HTTP request... connect timed out` error in AWS Glue. Written while I was on the Glue team, still read by customers globally.
- **AWS Builder Center**, building near real-time data pipelines with AWS DMS, full load plus CDC. `<!-- TODO: article URL -->`
- **BeSA "I Am a Cloud Builder"**, I host this community video series featuring AWS Community Builders, Heroes and User Group leaders.
- **[YouTube](https://youtube.com/@nirmalpatel008)**, AWS architecture, DMS/Glue/Athena walkthroughs, AI and developer-experience experiments, live demos.
- **[near-realtime-business-metrics](https://github.com/nirmalpatel008/near-realtime-business-metrics)**, open source. A DMS CDC pipeline with KPI queries, a dashboard, and Glue catalog integration.

---

## Selected work

**Credibly** · Senior AWS Data Engineer · Jan 2025 to May 2026

Designed and delivered the company's first production AWS data lake from scratch. Introduced change data capture as a new platform capability, which unlocked DynamoDB data the analytics team previously could not query at all.

Migrated 14 DMS replication tasks into a hardened production account, consolidating nine endpoints down to six. Multi-AZ r6i.xlarge replication instance, KMS encryption, Secrets Manager credentials, cross-account VPC peering across four source databases.

Designed dual S3 target endpoints, one high-frequency and one large-batch flush, to trade CDC latency against Glue Data Catalog churn deliberately rather than accidentally.

Wrote the architecture evaluation comparing DMS Serverless against Aurora Zero-ETL. That document is where my AWS Summit 2026 talk came from.

**AWS India** · Big Data Cloud Engineer, Glue SME · Sep 2021 to Dec 2024

Accredited as a Subject-Matter Expert for AWS Glue, the deepest technical specialist designation for that service inside the Big Data support organisation. Three years of debugging other people's Glue and Spark architectures at scale.

Built an internal MWAA plugin-packager in Python that removed the need for Docker-based local-runner setup. It became the standard ramp-up path org-wide for private MWAA environments.

PySpark ETL into Iceberg, Delta Lake, Redshift and Snowflake. Cross-account Glue catalog sharing through Lake Formation. Received the Rising Star award for top performance on the Big Data team.

**Appgambit** · Cloud Engineer · Jul 2020 to Jul 2021

Serverless SaaS products on AWS with Node.js and the Serverless Framework. CI/CD through CodeCommit, CodeDeploy, CodePipeline and CodeBuild.

---

## Stack

```
data & analytics    Glue (SME) · DMS · Athena · Lake Formation · MWAA · Redshift
                    QuickSight · Bedrock · Iceberg · Delta Lake

languages           Python · PySpark · SQL · Bash

datastores          Aurora MySQL · PostgreSQL · DynamoDB · Snowflake · S3

platform            CloudFormation (IaC) · Lambda · Step Functions · IAM · VPC
                    KMS · Secrets Manager · SQS · SNS · CloudWatch · EC2 · RDS

advocacy            public speaking · workshop facilitation · technical writing
                    live demos · community organising · developer experience
                    PoC and demo delivery · mentoring and enablement
```

---

## Certifications

<!-- Replace each href with your Credly credential URL. -->

| Credential | Issued |
| :--- | :--- |
| [AWS Certified Data Engineer, Associate (DEA-C01)](CREDLY_URL_HERE) | 2026 |
| [AWS Glue Subject-Matter Expert](CREDLY_URL_HERE) | Sep 2024 |
| [AWS Certified Solutions Architect, Associate](CREDLY_URL_HERE) | Jul 2021 |
| [AWS Certified Cloud Practitioner](CREDLY_URL_HERE) | Jul 2021 |
| [AWS Community Builder](CREDLY_URL_HERE) | Since 2021 |

B.E. Computer Engineering, CGPA 8.66/10, R.N.G. Patel Institute of Technology, Bardoli, 2016 to 2020. Now a Board of Studies member there.

---

## What I am looking for

Four kinds of role, in rough order of how much I want them.

<details>
<summary><b>Developer Advocacy / DevRel</b></summary>
<br/>

This is not a career change for me, it is the paid version of what I have been doing unpaid for years. I have run a user group, spoken at two AWS Summits, hosted a video series, written a Knowledge Center article read by thousands, and taught engineers inside AWS. The difference between me and a lot of DevRel candidates is that I also shipped the production systems, so the demo does not fall apart when someone asks a follow-up question.

Best fit: data infrastructure, cloud platforms, developer tooling, anything where the audience is engineers who will smell a shallow demo immediately.

</details>

<details>
<summary><b>Cloud Solutions Architect, Data & Analytics</b></summary>
<br/>

Three years inside AWS as a Glue SME meant seeing hundreds of customer architectures, most of them while broken. Then two years actually owning a platform end to end. I can scope a data platform, defend the tradeoffs in front of a customer, build the proof of concept, and run the enablement session afterwards.

</details>

<details>
<summary><b>Data & Analytics presales / solutions engineering</b></summary>
<br/>

The overlap of the two things above. Technical credibility in the room, plus the ability to explain a design to people who are not going to read the whitepaper. I have written architecture evaluation documents, conducted technical interviews, and presented tradeoffs to teams that had to make a decision that week.

</details>

<details>
<summary><b>Technical content and developer education</b></summary>
<br/>

Written docs, tutorials, video, workshops, course material. I also run <a href="https://cloudvidya.in">CloudVidya</a>, a cloud training venture working with engineering colleges across India, so the curriculum-design side is not theoretical for me either.

</details>

---

## Get in touch

Fastest ways to reach me:

**Email** [nmchhodvadiya008@gmail.com](mailto:nmchhodvadiya008@gmail.com)
**LinkedIn** [linkedin.com/in/nirmalchhodvadiya](https://linkedin.com/in/nirmalchhodvadiya)
**Everything else** [linktr.ee/nmchhodvadiya008](https://linktr.ee/nmchhodvadiya008)

If you are in or near Surat, the simplest option is to just come to a meetup and say hello.

<p align="left">
<img src="https://komarev.com/ghpvc/?username=nirmalpatel008&style=flat-square&color=FF9900&label=profile+views" />
<img src="https://img.shields.io/github/followers/nirmalpatel008?label=followers&style=flat-square&color=232F3E" />
</p>
