# Graph Report - sk-shieldus-rookies  (2026-11-19)

## Corpus Check
- Corpus is ~948 words - fits in a single context window. You may not need a graph.

## Summary
- 91 nodes · 109 edges · 7 communities
- Extraction: 82% EXTRACTED · 18% INFERRED · 0% AMBIGUOUS · INFERRED: 20 edges (avg confidence: 0.84)
- Token cost: 87,813 input · 0 output

## Community Hubs (Navigation)
- Network Security
- AWS Cloud Security
- Web App Security
- Python Security Automation
- Graphify Tooling
- Repo Rules & Credentials
- Course Overview

## God Nodes (most connected - your core abstractions)
1. `네트워크 보안` - 23 edges
2. `클라우드(AWS) 보안` - 19 edges
3. `애플리케이션(웹) 보안` - 18 edges
4. `파이썬 — 보안 자동화` - 11 edges
5. `graphify knowledge graph (graphify-out/)` - 9 edges
6. `클라우드 기반 스마트 융합보안 과정 (2026.09.16~2027.03.23, 960H)` - 5 edges
7. `SK쉴더스 루키즈 35기 실습 기록 저장소` - 4 edges
8. `SQL 인젝션` - 4 edges
9. `과목 1: 파이썬` - 3 edges
10. `자격증명 미포함 원칙 (.env + .gitignore)` - 3 edges

## Surprising Connections (you probably didn't know these)
- `액세스 키 커밋 금지` --semantically_similar_to--> `자격증명 미포함 원칙 (.env + .gitignore)`  [INFERRED] [semantically similar]
  cloud/README.md → README.md
- `보안그룹 / NACL` --semantically_similar_to--> `ACL`  [INFERRED] [semantically similar]
  cloud/README.md → network/README.md
- `VPN / Direct Connect` --semantically_similar_to--> `VPN / 터널링`  [INFERRED] [semantically similar]
  cloud/README.md → network/README.md
- `nmap` --semantically_similar_to--> `nmap`  [INFERRED] [semantically similar]
  web-security/README.md → network/README.md
- `위협 조회 → 차단 자동화` --semantically_similar_to--> `fail2ban`  [INFERRED] [semantically similar]
  python/README.md → network/README.md

## Hyperedges (group relationships)
- **자격증명 보호 원칙** — readme_credential_exclusion_policy, python_readme_env_file, cloud_readme_access_key_no_commit [INFERRED 0.85]
- **SQL 인젝션 공격·대응 흐름** — web_security_readme_sql_injection, web_security_readme_blind_sqli, web_security_readme_sqlmap, web_security_readme_prepared_statement [INFERRED 0.85]
- **graphify navigation commands** — claude_graphify_query, claude_graphify_path, claude_graphify_explain, claude_graphify_section [EXTRACTED 1.00]

## Communities (7 total, 0 thin omitted)

### Community 0 - "Network Security"
Cohesion: 0.11
Nodes (21): VPN / Direct Connect, ARP, CA (인증기관), 장비 설정 config/*.txt, DHCP Snooping, EtherChannel, FHRP, IPsec VPN (+13 more)

### Community 1 - "AWS Cloud Security"
Cohesion: 0.13
Nodes (18): 오토스케일링, AWS CLI, 클라우드(AWS) 보안, CloudWatch, DynamoDB, EBS, EC2, ELB (+10 more)

### Community 2 - "Web App Security"
Cohesion: 0.14
Nodes (18): nmap, 인증·인가 우회 · 파라미터 변조, BeEF · XSS 세션 탈취, Blind SQLi, Burp Suite, 파일 다운로드 취약점 (디렉터리 트래버설), IDOR, MITRE ATT&CK (+10 more)

### Community 3 - "Python Security Automation"
Cohesion: 0.22
Nodes (11): fail2ban, 제어문 (if/match-case/for/while/try-except), 기본 자료형 · 컬렉션 타입, Flask · Jinja2 웹 API, 함수 · 파일 · CSV/JSON, MongoDB (NoSQL), 객체지향(OOP) · 인프라 자동화, 파이썬 — 보안 자동화 (+3 more)

### Community 4 - "Graphify Tooling"
Cohesion: 0.20
Nodes (9): graphify skill (/graphify trigger), GRAPH_REPORT.md, graphify explain, graphify knowledge graph (graphify-out/), graphify path, graphify query, graphify section, graphify update . (+1 more)

### Community 5 - "Repo Rules & Credentials"
Cohesion: 0.29
Nodes (3): docs (회고·발표 자료·참고 링크), .env 파일, SK쉴더스 루키즈 35기 실습 기록 저장소

### Community 6 - "Course Overview"
Cohesion: 0.33
Nodes (6): 과목 3: 애플리케이션 보안, 과목 4: 클라우드 보안, 과목 2: 네트워크 보안, 과목 1: 파이썬, 보안 감사 자동화 엔진 (Ver.1 → Ver.2), 클라우드 기반 스마트 융합보안 과정 (2026.09.16~2027.03.23, 960H)

## Knowledge Gaps
- **45 isolated node(s):** `graphify skill (/graphify trigger)`, `graphify query`, `graphify path`, `graphify explain`, `graphify section` (+40 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 46 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `네트워크 보안` connect `Network Security` to `AWS Cloud Security`, `Web App Security`, `Python Security Automation`, `Course Overview`?**
  _High betweenness centrality (0.368) - this node is a cross-community bridge._
- **What connects `graphify skill (/graphify trigger)`, `graphify query`, `graphify path` to the rest of the system?**
  _45 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Network Security` be split into smaller, more focused modules?**
  _Cohesion score 0.10952380952380952 - nodes in this community are weakly interconnected._
- **Why does `클라우드(AWS) 보안` connect `AWS Cloud Security` to `Network Security`, `Repo Rules & Credentials`, `Course Overview`?**
  _High betweenness centrality (0.291) - this node is a cross-community bridge._
- **Should `AWS Cloud Security` be split into smaller, more focused modules?**
  _Cohesion score 0.13071895424836602 - nodes in this community are weakly interconnected._
- **Why does `애플리케이션(웹) 보안` connect `Web App Security` to `Repo Rules & Credentials`, `Course Overview`?**
  _High betweenness centrality (0.283) - this node is a cross-community bridge._
- **Should `Web App Security` be split into smaller, more focused modules?**
  _Cohesion score 0.1437908496732026 - nodes in this community are weakly interconnected._