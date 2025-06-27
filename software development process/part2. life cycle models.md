# Software Development Process - Part 2: Life Cycle Models

---

## 1. Software Development Life Cycle (SDLC) Phases

### 1.1 Requirements Engineering

Requirements Engineering is the process of identifying and documenting the needs and expectations of stakeholders. Errors in this phase are costly to fix later, as they affect all subsequent phases.

#### Key Activities:
- **Elicitation** – Gathering requirements from stakeholders.
- **Analysis** – Understanding and refining requirements.
- **Specification** – Clearly documenting requirements.
- **Validation** – Ensuring alignment with stakeholder needs.
- **Management** – Handling changes and maintaining traceability.

> 🔁 These steps are iterative rather than strictly linear.

---

### 1.2 Design

Design translates requirements into a structured solution that can be implemented and verified.

#### Design Activities:
1. **Architectural Design** – High-level system structure.
2. **Abstract Specification**
3. **Interface Design**
4. **Component Design**
5. **Data Structure Design**
6. **Algorithm Design** – Low-level implementation logic.

#### Design Products:
- System architecture
- Software & interface specifications
- Component specifications
- Data structures & algorithms

---

### 1.3 Implementation

This phase involves translating design into working software.

#### Four Key Principles:
1. **Reduction of Complexity**
2. **Anticipation of Diversity**
3. **Structuring for Validation**
4. **Use of External Standards**

---

### 1.4 Verification & Validation (V&V)

- **Validation** – *"Did we build the right system?"*
- **Verification** – *"Did we build the system right?"*

Both are essential for ensuring quality and correctness.

---

### 1.5 Maintenance

After release, software requires ongoing updates and fixes.

#### Types of Maintenance:
- **Corrective** – Fixing bugs.
- **Perfective** – Improving features.
- **Adaptive** – Adjusting to environmental changes.

> ⚠️ **Regression Errors**: New updates may break existing functionality. Regression testing helps catch these.

---

## 2. Software Process Models

A software process model defines how development activities are organized.

---

### 2.1 Waterfall Model

**Phases**:  
Software Concept → Requirements Analysis → Architectural Design → Detailed Design → Coding → Testing

**Pros**:
- Structured and easy to follow.
- Good for projects with stable requirements.

**Cons**:
- Inflexible to changes once development begins.
- Late discovery of requirement flaws.

---

### 2.2 Spiral Model

**Cycle per iteration**:
1. Determine Objectives
2. Identify & Resolve Risks
3. Develop & Test
4. Plan Next Iteration

**Pros**:
- Early feedback from users.
- Risk-focused and flexible.

**Cons**:
- Complex management.
- Requires skilled risk analysis.

---

### 2.3 Evolutionary Prototyping

**Process**:
Initial Concept → Build Prototype → Refine via Feedback → Final Product

**Pros**:
- Fast feedback loop with users.
- Good for unclear or evolving requirements.

**Cons**:
- Difficult to plan schedules and resources.
- Risk of evolving prototype into messy production code.

---

### 2.4 Agile Process

**Key Traits**:
- Iterative and incremental.
- Emphasizes collaboration and rapid feedback.

#### TDD (Test-Driven Development):
1. Write failing tests.
2. Write minimal code to pass tests.
3. Refactor for quality.
4. Repeat.

**Pros**:
- High adaptability.
- Frequent deliverables.

**Cons**:
- Requires discipline and collaboration.
- Less focus on documentation.

---

### 2.5 How to Choose the Right Model?

Factors to consider:
- **Clarity of Requirements**
- **Expected Lifetime of Software**
- **Risk Levels**
- **Time and Schedule Constraints**
- **Level of Customer Involvement**
- **Team Expertise**

> ✅ No one-size-fits-all model. Choose based on project needs and constraints.

---

## 3. Classic Mistakes in Software Development

Avoiding common pitfalls can significantly improve project success.

---

### 3.1 People

- **Heroics** – Relying on lone "heroes" instead of fostering collaboration.
- **Poor Work Environment** – Lack of support, tools, or clear roles.
- **Bad People Management** – Misaligned roles, lack of motivation.

---

### 3.2 Process

- **Scheduling Issues** – Unrealistic deadlines and poor estimates.
- **Planning Issues** – Incomplete, unclear, or inflexible plans.

---

### 3.3 Product

- **Gold Plating** – Adding unneeded polish or extras.
- **Feature Creep** – Uncontrolled addition of features.
- **Research ≠ Development** – Mismanaging exploration as execution.

---

### 3.4 Technology

- **Silver-Bullet Syndrome** – Belief that new tools/tech alone will fix problems.
- **Tool Switching** – Mid-project tool changes harm productivity.
- **Lack of Version Control** – No proper code/artifact tracking leads to chaos.

---

> 🚨 Most classic mistakes are avoidable through awareness, planning, and disciplined practices.

