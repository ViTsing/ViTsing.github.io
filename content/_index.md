---
# Leave the homepage title empty to use the site title
title: "Home Page of Ming Dong"
date: 2024-12-10
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: Ming Dong
    design:
      columns: '2'
  
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  
  - block: collection
    id: projects
    content:
      title: Current Projects
      text: |
        1. Research on the Application of Large Language Models in School Education and Teaching (National Language Committee Project, 2025-2026)
        2. Intelligent Question Answering System for Structured Data Based on Large Models (Industry Collaboration, 2025-2026)
        3. Research on Multilingual Pre-training Models Integrating Chinese Rich Semantic Knowledge (China Postdoctoral Science Foundation, 2024-2026)
        4. Research on Optimization Strategies of Large Language Models Driven by Chinese Rich Semantics (Hubei Natural Science Foundation Youth Project, 2023-2025)
    design:
      columns: '2'
      view: list
  
  - block: experience
    id: teaching
    content:
      title: Teaching
      items:
        - title: Machine Learning
          company: CCNU
          date_start: '2023-01-01'
          date_end: '2025-06-30'
          description: Spring semesters 2023-2025
        
        - title: Computer Fundamentals
          company: CCNU
          date_start: '2023-09-01'
          date_end: '2024-12-31'
          description: Fall semesters 2023-2024
        
        - title: Pattern Recognition and Image Processing
          company: CCNU
          date_start: '2022-01-01'
          date_end: '2022-06-30'
          description: Spring semester 2022
    design:
      columns: '2'
  
  - block: contact
    id: contact
    content:
      title: Contact
      email: dongming@ccnu.edu.cn
      address:
        street: Room 7065, Nanhu Complex Building
        city: Wuhan
        region: Hubei
        country: China
        country_code: CN
      directions: School of Computer Science, Central China Normal University
    design:
      columns: '2'

## About Me

I am currently a faculty member at the School of Computer Science, Central China Normal University (CCNU). I received my Ph.D. in Computer Software and Theory from Huazhong University of Science and Technology in September 2021. My research interests include Natural Language Processing, Chinese Information Processing, and AI in Education.

## Research Interests
- Natural Language Processing
- Chinese Information Processing
- Artificial Intelligence in Education

## Selected Publications
1. **Ming Dong**, Zhiwei Cheng, Changyin Luo, Tingting He*. "Retrieval-Augmented Generation for Large Language Model based Few-shot Chinese Spell Checking." COLING 2025.

2. **Ming Dong**, Yujing Chen, Miao Zhang, Hao Sun, Tingting He*. "Rich Semantic Knowledge Enhanced Large Language Models for Few-shot Chinese Spell Checking." ACL Findings 2024.

3. Miao Zhang, Tingting He*, **Ming Dong***. "Meta-path Reasoning of Knowledge Graph for Commonsense Question Answering." Frontiers of Computer Science, 2024.

4. **Ming Dong**, Bolong Zheng*, Guohui Li, et al. "Wavefront based Multiple Rumor Sources Identification by Multi-Task Learning." IEEE Transactions on Emerging Topics in Computational Intelligence, 2022.

## Academic Service
- Program Committee Member: ACL Rolling Review (2023-2024), CCL2024, IJCNN2024, BIGDATA2023
- Reviewer for journals: IEEE/ACM TASLP, Information Processing & Management
