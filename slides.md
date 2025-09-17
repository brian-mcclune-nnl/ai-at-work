---
marp: true
theme: default
class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

# AI at NNL
## Practical AI Adoption in IST

**Navigating the Future of Software Development**

---

# About This Discussion

- **Current State**: Slow but steady AI adoption
- **Available Tools**: Chat assistants, IDE integration expanding
- **Our Team**: Mix of early adopters, skeptics, and concerned colleagues
- **Goal**: Responsible, practical AI integration

---

# Agenda

1. 🤖 What is AI? (10,000-foot view)
2. 🛠️ Types of AI Tools Available
3. 💡 How We Can Use Them
4. ⚠️ Addressing Concerns & Best Practices
5. 🚀 Next Steps for Our Team

---

# What is AI? 
## (The Obligatory 10,000-Foot View)

---

# AI Fundamentals

**Artificial Intelligence**: Systems that can perform tasks typically requiring human intelligence

**Key Components:**
- **Machine Learning**: Systems that improve through experience
- **Neural Networks**: Computing systems inspired by biological neural networks
- **Large Language Models (LLMs)**: AI trained on vast text datasets to understand and generate language

---

# How Modern AI Works (Simplified)

```
Training Data → Model Training → Inference
    📚            🧠             💬
Massive text    Learning        Generating
corpus          patterns        responses
```

1. **Training**: AI learns patterns from enormous datasets
2. **Fine-tuning**: Specialized training for specific tasks
3. **Inference**: Using trained model to generate responses
4. **Context**: AI uses conversation history to maintain coherence

---

# AI Code Generation & Assistance

**Current Capabilities:**
- Generate functional code across programming languages
- Provide context-aware completions with project understanding
- Convert between languages and scientific computing libraries
- Create comprehensive documentation, tests, and API references
- Implement complex algorithms from research papers
- Generate numerical analysis and simulation code

---

# AI Autonomous Actions (Emerging)

**What's Happening Now:**
- Execute code in sandboxed environments to test solutions
- Complete multi-step projects with development tools
- GitHub agents: Assigned to issues, create PRs automatically
- End-to-end problem solving: Requirements → Implementation
- Create data processing pipelines and visualization workflows
- Translate mathematical equations into optimized code

---

# Where Human Oversight is Critical

**Scientific Validation:**
- Ensuring computational accuracy and domain correctness
- Verifying algorithm implementation matches theory
- Validating results against known benchmarks

**Production & Security:**
- Security review and vulnerability assessment
- Compliance with government regulations
- System integration and deployment strategies

---

# Human Expertise Still Essential

**Research & Domain Knowledge:**
- Understanding experimental design and hypothesis testing
- Interpreting results within scientific context
- Making decisions about methodology and approach

**Performance & Optimization:**
- Hardware-specific tuning and scalability decisions
- Resource allocation and computational efficiency
- Real-world performance under production loads

---

# Types of AI Tools Available

---

# 1. Chat-Based Assistants

**Examples:** ChatGPT, Claude, Gemini, Copilot Chat

<div style="display: flex; gap: 2rem;">

<div style="flex: 1;">

**Characteristics:**
- Conversational interface in web browser or app
- Good for: Research, brainstorming, explaining concepts
- Requires manual copy/paste for code integration
- Often has access to broader knowledge base

</div>

<div style="flex: 1;">

**Best Use Cases:**
- Architectural discussions
- Code review and debugging help
- Learning new technologies
- Documentation and explanation

</div>

</div>

---

# 2. IDE-Integrated Assistants  

**Examples:** GitHub Copilot, Codeium, Amazon CodeWhisperer

<div style="display: flex; gap: 2rem;">

<div style="flex: 1;">

**Characteristics:**
- Direct integration with your development environment
- Real-time code suggestions and autocompletion
- Context-aware of your current project
- Seamless workflow integration

</div>

<div style="flex: 1;">

**Best Use Cases:**
- Code completion while typing
- Generating boilerplate code
- Writing unit tests
- Refactoring assistance

</div>

</div>

---

# 3. Additional AI Development Tools

**AI-Powered Editors & Code Completion:**
- **Cursor**: AI-first code editor with chat integration
- **Tabnine**: Advanced code completion and suggestions

**Command Line & Terminal:**
- **GitHub Copilot CLI**: Natural language to shell commands
- **Aider**: AI pair programming in terminal
- **Claude Code**: AI coding assistant for terminal workflows

**Enterprise & Productivity:**
- **MS 365 Copilot**: Integrated productivity AI across Office apps

---

# How We Can Use AI Tools

---

# 1. Learning & Research Phase

**🎓 For New Technologies:**
- "Explain microservices architecture for a .NET developer"
- "What are the security implications of GraphQL?"
- "Compare authentication approaches for government applications"

**📚 Documentation & Standards:**
- Generate API documentation templates
- Create coding standard explanations
- Translate legacy documentation to current formats

**💡 Tip:** Start here if you're skeptical - use AI for learning, not production code

---

# 2. Planning & Architecture

<div style="display: flex; gap: 1.5rem;">

<div style="flex: 1;">

**🏗️ System Design:**
- Brainstorm architectural approaches
- Evaluate trade-offs between solutions
- Generate technical specifications

</div>

<div style="flex: 1;">

**📋 Project Planning:**
- Break down complex features into tasks
- Estimate development effort
- Create implementation roadmaps

</div>

<div style="flex: 1;">

**🔍 Code Reviews:**
- Identify potential issues in existing code
- Suggest refactoring opportunities
- Explain complex code sections to team members

</div>

</div>

---

# 3. Active Development

<div style="display: flex; gap: 1.5rem;">

<div style="flex: 1;">

**⌨️ Code Generation:**
- Boilerplate code and templates
- Unit test generation
- Configuration file creation

</div>

<div style="flex: 1;">

**🐛 Debugging:**
- Analyze error messages and stack traces
- Suggest debugging approaches
- Generate test cases to reproduce issues

</div>

<div style="flex: 1;">

**🔄 Refactoring:**
- Modernize legacy code patterns
- Improve code readability
- Optimize performance bottlenecks

</div>

</div>

---

# 4. Documentation & Communication

<div style="display: flex; gap: 1.5rem;">

<div style="flex: 1;">

**📝 Technical Writing:**
- README files and setup instructions
- API documentation and examples
- Architecture decision records (ADRs)

</div>

<div style="flex: 1;">

**💬 Team Communication:**
- Explain technical concepts to non-technical stakeholders
- Create status updates and progress reports
- Generate meeting agendas and summaries

</div>

<div style="flex: 1;">

**🎯 Government-Specific:**
- Compliance documentation assistance
- Security review checklists
- Audit trail documentation

</div>

</div>

---

# Progressive Adoption Strategy

**🟢 Start Small (Low Risk)**
```
Documentation → Learning → Discussion
```

**🟡 Build Confidence (Medium Risk)**  
```
Code Review → Architecture Planning → Prototyping
```

**🔴 Full Integration (Higher Risk)**
```
Production Code → Automated Workflows → Critical Systems
```

**Remember:** You control the pace and scope of adoption

---

# Addressing Concerns & Best Practices

---

# 1. Am I risking leaking data? What am I allowed to use?

**� Data Protection Guidelines:**
- Use private (NNPP) services where possible and appropriate
- Do not enter Program information into public services
- See CP-207 (Corporate Policy for Use of Generative Artificial Intelligence) for more information

---

# 2. How do I know the AI is right? What about hallucinations?

**🔍 Always Verify:**
- Treat AI output as a starting point, not final solution
- Test all AI-generated code thoroughly
- Maintain coding standards regardless of source

**� Ask Follow-up Questions:**
- "What sources inform this recommendation?"
- "Can you provide documentation links?"
- "What are the potential drawbacks of this approach?"

---

# 3. Is this stealing? What about data provenance?

**⚖️ Ethical Considerations:**
- AI/model developers are increasingly focused on responsible and ethical sourcing
- Major companies are investing in transparent data provenance practices

**🤔 For Skeptics - Start Here:**
- **Discussion Only**: Use AI for brainstorming and learning, not code generation
- **Ask for Sources**: "Where can I verify this information?" and cross-check responses

---

# Next Steps for Our Team

---

# Immediate Actions (This Month)

**🏢 Organizational:**
- [ ] Form AI adoption working group
- [ ] Review and approve initial AI tools with IT security
- [ ] Establish usage guidelines and best practices
- [ ] Create documentation templates for AI assistance

**👥 Team Level:**
- [ ] Survey team for current AI usage and interest levels
- [ ] Identify early adopters willing to mentor others
- [ ] Schedule lunch-and-learn sessions
- [ ] Start with low-risk documentation and learning tasks

---

# Short Term (Next 3 Months)

**📚 Learning & Training:**
- Organize hands-on workshops with approved AI tools
- Create internal knowledge sharing sessions
- Develop government-specific use case examples
- Build confidence through guided practice

**🔧 Pilot Projects:**  
- Select non-critical projects for AI experimentation
- Document lessons learned and best practices
- Measure impact on productivity and code quality
- Refine adoption guidelines based on experience

---

# Long Term Vision (6-12 Months)

**🚀 Mature Integration:**
- AI tools become natural part of development workflow
- Team members choose appropriate tools for each task
- Established patterns for responsible AI usage
- Measurable improvements in development efficiency

**📊 Continuous Improvement:**
- Regular assessment of AI tool effectiveness
- Stay current with evolving AI capabilities
- Contribute to government-wide AI adoption standards
- Share success stories with other organizations

---

# Getting Started Today

**For Skeptics:** 
- Try asking ChatGPT or Claude to explain a technology concept
- Request sources and verify the information independently
- Start with learning, not code generation

**For Curious Colleagues:**
- Install GitHub Copilot or similar IDE integration
- Use it for generating comments and documentation first
- Practice with personal/learning projects before work code

**For Early Adopters:**
- Share your experiences and help establish team guidelines  
- Mentor colleagues who want to learn
- Help identify the most valuable use cases for our work

---

# Key Takeaways

✅ **AI is a powerful tool** that can augment human capabilities

✅ **Start small** with low-risk applications like documentation and learning

✅ **Maintain human oversight** and verification for all AI assistance

✅ **Address concerns proactively** with clear guidelines and best practices

✅ **Build confidence gradually** through successful, incremental adoption

✅ **Work together** to establish responsible AI practices for our organization

---

# Questions & Discussion

**Let's explore your specific concerns and use cases:**

- What AI tools have you already tried?
- What aspects of your work could benefit from AI assistance?
- What are your biggest concerns about AI adoption?
- How can we establish trust and confidence in our team?

**Remember:** This is a journey, not a destination. We'll learn and adapt together.

---

# Resources & Contact

**Documentation:**
- Internal AI Guidelines: *[Link to be added]*
- Approved Tools List: *[Link to be added]*
- Security Requirements: *[Link to be added]*

**Training Materials:**
- AI Fundamentals for Developers
- Prompt Engineering Best Practices  
- Government AI Ethics Guidelines

**Questions?** Feel free to reach out for guidance on responsible AI adoption.

*Let's build the future of government software development together.*
