# Team Project Plan --- Introduction to Artificial Intelligence

> **Working draft for GitHub**\
> **Main reference:** Wolfgang Ertel, *Introduction to Artificial
> Intelligence*, 3rd Edition, Springer.\
> **Proposed module:** Search and Problem Solving in Artificial
> Intelligence\
> **Stage 1 deadline:** 24 October 2026, 23:59 Beijing time\
> **Stage 2 deadline:** 7 November 2026\
> **Stage 3 deadline:** 28 November 2026

> **Before submission:** Replace every `[PLACEHOLDER]` with your team's
> real information. Confirm that "Search and Problem Solving in AI" is
> included in your teacher's approved topic menu and check the relevant
> book chapters/pages. Do not submit invented names, IDs, or
> contribution records.

------------------------------------------------------------------------

## 1. Team Information and Responsibilities

-   **Team name:** `[Fengwei Fried Rice]`
-   **Selected project module:** Search and Problem Solving in
    Artificial Intelligence
-   **GitHub repository:** `[https://github.com/benedictttt110/CS-AI-Project]`
-   **Submission lead:** `[MEMBER NAME]`

  ------------------------------------------------------------------------------------------------------------------------------------------------
  Member          Student ID  Relevant strengths / experience            Skills to develop                        Main             Backup /
  (class-roster                                                                                                   responsibility   collaboration
  name)                                                                                                                            
  --------------- ----------- ------------------------------------------ ---------------------------------------- ---------------- ---------------
  `[Member 1]`    `[ID]`      `[e.g., coordination, clear writing]`      `[e.g., GitHub Markdown]`                Project          Review all
                                                                                                                  coordinator;     sections and
                                                                                                                  maintain plan    help resolve
                                                                                                                  and task list;   blockers
                                                                                                                  check progress   

  `[Member 2]`    `[ID]`      `[e.g., mathematics, logical reasoning]`   `[e.g., explaining search algorithms]`   Lead research    Verify examples
                                                                                                                  and draft core   and algorithm
                                                                                                                  explanations     steps

  `[Member 3]`    `[ID]`      `[e.g., programming, diagrams]`            `[e.g., academic referencing]`           Develop worked   Review
                                                                                                                  examples and     technical
                                                                                                                  visual diagrams; accuracy
                                                                                                                  support slides   

  `[Member 4]`    `[ID]`      `[e.g., speaking, video editing]`          `[e.g., AI concepts / Markdown]`         Coordinate video Review learning
                                                                                                                  tutorial plan    activities and
                                                                                                                  and mini-lecture accessibility
                                                                                                                  rehearsal        
  ------------------------------------------------------------------------------------------------------------------------------------------------

**If the team has fewer or more than four members:** Add or remove rows
and redistribute tasks. Every member must study the module, make a
substantive content contribution, review another member's work, and be
able to explain the core ideas. Roles identify leads; they do not
restrict participation to one area.

### Fair workload approach

-   Break large deliverables into small tasks with visible outcomes.
-   Assign each task one lead and, where useful, a reviewer.
-   Compare task size and estimated effort at each team meeting, not
    only the number of tasks.
-   Reassign work early if a member is overloaded or a task is blocked.
-   Record actual contributions and significant AI assistance honestly
    in the project and personal logs.

------------------------------------------------------------------------

## 2. Project Scope and Learning Goals

### 2.1 Target learners

Beginner undergraduate students who are new to artificial intelligence.
Learners are expected to understand basic programming ideas such as
variables, conditions, and lists, but **no prior AI course or advanced
mathematics is assumed**. The materials will explain technical terms
before using them.

### 2.2 Learning goals

After using the materials, learners should be able to:

1.  Explain what a search problem is and identify its **initial state,
    actions, transition model, goal test, and path cost**.
2.  Distinguish a state-space representation from the path used to reach
    a goal.
3.  Describe and trace Breadth-First Search (BFS) and Depth-First Search
    (DFS) on a small graph.
4.  Explain, at an introductory level, how Uniform-Cost Search and
    Greedy Best-First Search differ.
5.  Explain the purpose of a heuristic and how A\* combines path cost so
    far with an estimate of the remaining cost.
6.  Compare selected search methods using completeness, optimality,
    time, and memory in simple terms.
7.  Choose a suitable search method for a small example and justify the
    choice.
8.  Check a search trace for errors and explain why an algorithm visits
    states in a particular order.

### 2.3 Content outline

#### Topic 1 --- AI problem solving and state spaces

-   What problem solving means in AI
-   States, actions, transitions, goal states, and path costs
-   A small route-finding or puzzle example
-   How to represent a problem as a graph

#### Topic 2 --- Uninformed search

-   Breadth-First Search (BFS): queue and level-by-level exploration
-   Depth-First Search (DFS): stack/recursion and exploring one branch
-   Step-by-step trace on the same small graph
-   Introductory comparison: completeness, optimality, time, and memory

#### Topic 3 --- Cost-based and heuristic search

-   Uniform-Cost Search: expanding the lowest accumulated path cost
-   Heuristics: estimates that guide search
-   Greedy Best-First Search: prioritizing the heuristic estimate
-   A\* Search: combining cost so far and estimated remaining cost
-   Small worked example comparing the order of expansion

#### Topic 4 --- Practice and review

-   Trace an algorithm from a given start state
-   Select a search method for a scenario and explain why
-   Short conceptual questions and answer explanations
-   Common mistakes and a final self-check

### 2.4 Scope boundaries

**Detailed coverage:** state-space formulation, BFS, DFS, basic
heuristic ideas, and an introductory A\* example.

**Brief introduction only:** Uniform-Cost Search and Greedy Best-First
Search as comparison points; formal proofs of completeness/optimality;
advanced heuristic design; adversarial/game search; constraint
satisfaction; and implementation optimizations.

**Out of scope for this module:** a full survey of all AI fields, deep
learning, neural-network training, and advanced mathematical proofs.
These belong to other modules or require more background.

### 2.5 Questions to confirm with the teacher

-   Is "Search and Problem Solving in AI" an approved module from the
    course topic menu?
-   Which chapters or sections of Ertel's third edition should be
    treated as the main coverage?
-   Should pseudocode be sufficient, or is executable code expected?
-   How many test-bank questions and video tutorials are expected?
-   Are there specific requirements for the mini-lecture duration or
    presentation format?

------------------------------------------------------------------------

## 3. Planned Learning Resources and Mini Lecture

The **shared Markdown content is the source of truth**. The Study Guide,
test bank, slides, and video scripts will be derived from it so
definitions, examples, and answers remain consistent.

### 3.1 Shared Markdown content

Proposed repository structure:

``` text
[repository]/
├── README.md
├── PLAN.md
├── CONTRIBUTIONS.md
├── AI_USE_LOG.md
├── references/
│   └── SOURCES.md
├── content/
│   ├── 01-ai-problem-solving.md
│   ├── 02-uninformed-search.md
│   ├── 03-heuristic-search.md
│   └── 04-practice-and-review.md
├── study-guide/
│   └── TEST_BANK.md
├── slides/
│   └── SLIDE_OUTLINE.md
├── videos/
│   └── VIDEO_SCRIPTS.md
└── mini-lecture/
    └── MINI_LECTURE_PLAN.md
```

Each topic file should include: - Learning objectives - Plain-language
explanation of each key term - A worked example with every important
step shown - A diagram or table where it helps understanding - A short
learner activity or check-for-understanding question - Common errors or
misconceptions - Answers or explanations where applicable - References
for factual claims, diagrams, and adapted examples

### 3.2 Study Guide and Test Bank

**Study Guide structure** 1. Learning objectives and prerequisite
knowledge 2. Key vocabulary 3. Search problem and state-space
representation 4. BFS and DFS explanations with worked traces 5.
Cost-based and heuristic search overview 6. A\* worked example 7.
Comparison table and common mistakes 8. Summary and self-check

**Test Bank plan** - Short-answer questions checking core definitions -
Graph-tracing questions for BFS and DFS - Questions interpreting
heuristic values and A\* priorities - Comparison / method-selection
questions - Answer key with explanations, not only final answers

The initial target is **10--15 questions**, with a mix of recall,
tracing, and reasoning. Confirm the expected number with the teacher.

### 3.3 PPT Slides

Planned slide sequence: 1. Title, audience, and learning objectives 2.
What is an AI search problem? 3. State-space graph and key components 4.
BFS animation or step-by-step graph trace 5. DFS trace on the same graph
6. Comparing BFS and DFS 7. Heuristics and the idea behind A\* 8. Worked
example and method-selection activity 9. Summary and one-minute review
question 10. References

Use readable diagrams, limited text, consistent notation, and the same
examples as the Markdown and Study Guide.

### 3.4 Video Tutorials

Proposed short tutorials: - **Video 1:** Turning a real-world task into
a state-space search problem. - **Video 2:** Tracing BFS and DFS on a
small graph. - **Video 3:** Understanding heuristics and the basic idea
of A\*.

Each script should include the learning objective, narration, on-screen
diagram or demonstration, a pause-and-predict question, and a brief
recap. Keep each video focused on one concept; final duration will be
decided after drafting.

### 3.5 Live Mini Lecture

-   **Proposed topic:** "How does A\* Search find a promising route?"
-   **Why it matters:** It demonstrates how an AI search algorithm can
    use both the cost already travelled and an estimate of the cost
    remaining.
-   **Central question:** "If two possible routes are available, which
    state should A\* explore next, and why?"
-   **Teaching approach:** Show a small route graph with edge costs and
    simple heuristic values. Ask the audience to predict the next state,
    then calculate `f(n) = g(n) + h(n)` together and compare the choice
    with Greedy Best-First Search.
-   **Audience activity:** Learners select the next node and explain
    their choice to a partner or by a quick poll.
-   **Planned check:** One final question asking learners to identify
    `g(n)`, `h(n)`, and `f(n)` for a node.

Confirm the topic against the teacher's approved topic menu and the
live-presentation time limit before finalizing.

### 3.6 How the resources connect

  -----------------------------------------------------------------------------
  Shared concept Study Guide    PPT Slides       Video Tutorials Mini Lecture
  -------------- -------------- ---------------- --------------- --------------
  State-space    Definitions    Graph diagram    Worked          Brief route
  model          and practice                    modelling       example
                                                 example         

  BFS and DFS    Full traces    Side-by-side     Step-by-step    Used as prior
                 and questions  visual           graph           knowledge if
                                comparison       demonstration   needed

  Heuristics and Explanation    Cost/heuristic   Narrated A\*    Main teaching
  A\*            and exercises  diagram          trace           focus
  -----------------------------------------------------------------------------

Any correction to a definition, algorithm trace, or answer must first be
made in the shared Markdown, then propagated to every affected resource.

------------------------------------------------------------------------

## 4. Workflow, Schedule, and Coordination

### 4.1 Milestones and internal deadlines

  ----------------------------------------------------------------------------
  Stage             Official deadline Internal          Main outputs
                                      checkpoint        
  ----------------- ----------------- ----------------- ----------------------
  Stage 1           24 Oct 2026       23 Oct: peer      Approved plan,
                                      review; 24 Oct:   detailed task list,
                                      final check and   repository, initial
                                      submission        substantive Markdown
                                                        content as required by
                                                        the course

  Stage 2           7 Nov 2026        5 Nov: draft      First versions of
                                      freeze; 6 Nov:    Study Guide, test
                                      review and        bank, slides, video
                                      rehearsal         scripts/recordings as
                                                        required; mini-lecture
                                                        preparation/delivery
                                                        according to class
                                                        schedule

  Stage 3           28 Nov 2026       24 Nov: feedback  Revised and checked
                                      collected; 26     resources, final
                                      Nov: corrections  delivery, contribution
                                      complete; 27 Nov: and AI-use records
                                      final audit       
  ----------------------------------------------------------------------------

**Important:** The planning assignment and the separate requirement for
a substantive Markdown V1.0 may be different submission components.
Check the course instructions and ensure the Stage 1 repository contains
actual learning content, not only this plan.

### 4.2 Working method

1.  **Study first:** Each member reads the assigned textbook sections
    and at least one reliable supporting source relevant to their task.
2.  **Draft in Markdown:** Write explanations, examples, diagrams, and
    activities in the shared repository before creating polished slides
    or videos.
3.  **Review content:** A member other than the author checks technical
    accuracy, clarity for beginners, examples, and references.
4.  **Produce resources:** Use the approved Markdown as the basis for
    the Study Guide, slides, and video scripts.
5.  **Cross-check:** Compare every diagram, formula, algorithm trace,
    and answer across all deliverables.
6.  **Test with learners:** Ask at least one peer unfamiliar with the
    draft to complete an activity and identify confusing explanations.
7.  **Revise and document:** Apply feedback, update affected resources,
    and log contributions and significant AI assistance.

### 4.3 GitHub and communication

-   Use GitHub as the shared workspace and contribution record.
-   Create an issue for each meaningful task; include an owner, expected
    result, and deadline.
-   Use descriptive branch names where appropriate, such as
    `content/bfs-dfs`.
-   Make focused commits with clear messages.
-   Open pull requests or request peer review before merging substantial
    content.
-   Avoid overwriting another member's work; discuss conflicts before
    resolving them.
-   Meet briefly at least twice per week until Stage 2, then weekly or
    as needed through Stage 3.
-   Use `[GROUP CHAT / PLATFORM]` for urgent questions and
    `[MEETING LOG LOCATION]` for decisions.
-   The coordinator updates this plan and task statuses after each
    meeting.
-   The submission lead checks file naming, links, readability, and
    required evidence before submitting.

### 4.4 Content quality checklist

Before a section is marked complete, check: - \[ \] Definitions are
accurate and written in beginner-friendly language. - \[ \] Every worked
example shows the important intermediate steps. - \[ \] Graphs, node
labels, costs, and algorithm traces agree. - \[ \] Exercises have answer
explanations and have been independently checked. - \[ \] Sources are
cited; reused material is clearly attributed. - \[ \] The content is
original in wording and does not rely on unattributed copying. - \[ \]
The Study Guide, slides, and video script use consistent terms and
examples. - \[ \] A peer has reviewed the section and feedback has been
addressed.

### 4.5 Main risks and responses

  -----------------------------------------------------------------------
  Risk                                Response
  ----------------------------------- -----------------------------------
  Members are unfamiliar with GitHub  Hold a short setup session; use a
  or Markdown                         small test edit before drafting
                                      major content

  Search algorithms are difficult to  Work through one shared example
  explain accurately                  together and have a second member
                                      verify each trace

  Workload becomes uneven             Review task effort weekly, split
                                      large tasks, and reassign early

  Research or drafting is delayed     Use internal deadlines earlier than
                                      official deadlines and flag
                                      blockers in the group chat

  Resources contradict one another    Treat Markdown as the source of
                                      truth and run a cross-resource
                                      consistency check

  Video or presentation production    Finalize scripts and diagrams
  takes longer than expected          first; keep a simpler backup format
                                      ready

  AI-generated content contains       Verify claims against the textbook
  errors or weak citations            or reliable sources; log AI use and
                                      revise in the team's own words
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 5. Master Task List

**Status values:** `Not started` · `In progress` · `Under review` ·
`Completed` · `Blocked`

Replace placeholder owners with real names. Keep this table updated.
Tasks for Stages 2 and 3 are intentionally broader and should be broken
down as the project develops.

  ----------------------------------------------------------------------------------------------------------------------------------------
  ID       Stage    Task               Expected result                       Responsible member(s)    Internal   Status     Dependencies
                                                                                                      deadline              
  -------- -------- ------------------ ------------------------------------- ------------------------ ---------- ---------- --------------
  S1-01    1        Confirm team name, Completed team information table      `[Coordinator]`; all     21 Oct     In         None
                    roster names,                                            members verify                      progress   
                    student IDs, and                                                                                        
                    contact channel                                                                                         

  S1-02    1        Confirm the module Scope decision and chapter/section    `[Research lead]`; all   21 Oct     Not        Course topic
                    is allowed by the  notes in `references/SOURCES.md`      members review                      started    menu and book
                    teacher and map it                                                                                      
                    to the textbook                                                                                         
                    sections                                                                                                

  S1-03    1        Read relevant      Shared research notes with citations  All members;             22 Oct     Not        S1-02
                    textbook sections                                        `[Research lead]`                   started    
                    and record key                                           coordinates                                    
                    concepts and page                                                                                       
                    references                                                                                              

  S1-04    1        Finalize target    Approved learner profile and          `[Coordinator]` +        22 Oct     Not        S1-03
                    learners and       learning-goal list in `PLAN.md`       `[Content lead]`                    started    
                    measurable                                                                                              
                    learning goals                                                                                          

  S1-05    1        Define the module  Topic/subtopic outline and            `[Content lead]`; all    22 Oct     Not        S1-03
                    outline and scope  in-scope/out-of-scope list            members review                      started    
                    boundaries                                                                                              

  S1-06    1        Create repository  Repository structure ready for        `[GitHub lead]`          22 Oct     Not        S1-01
                    folders and        collaboration                                                             started    
                    initial files                                                                                           

  S1-07    1        Draft the          `content/01-ai-problem-solving.md`    `[Member 2]`; reviewer   23 Oct     Not        S1-05, S1-06
                    explanation of     with a worked example                 `[Member 3]`                        started    
                    search problems                                                                                         
                    and state-space                                                                                         
                    representation                                                                                          

  S1-08    1        Draft BFS and DFS  `content/02-uninformed-search.md`     `[Member 3]`; reviewer   23 Oct     Not        S1-05, S1-06
                    explanations and   with checked traces                   `[Member 2]`                        started    
                    trace both on one                                                                                       
                    graph                                                                                                   

  S1-09    1        Draft introductory `content/03-heuristic-search.md` with `[Member 2]`; reviewer   23 Oct     Not        S1-05, S1-06
                    heuristic-search   a small worked example                `[Member 4]`                        started    
                    and A\* content                                                                                         

  S1-10    1        Draft practice     `content/04-practice-and-review.md`   `[Member 4]`; all        23 Oct     Not        S1-07 to S1-09
                    activities, common                                       members contribute                  started    
                    mistakes, and                                                                                           
                    initial review                                                                                          
                    questions                                                                                               

  S1-11    1        Draft the resource Resource outlines and                 `[Member 4]`;            23 Oct     Not        S1-04, S1-05
                    plan and           `mini-lecture/MINI_LECTURE_PLAN.md`   coordinator checks                  started    
                    mini-lecture                                                                                            
                    proposal                                                                                                

  S1-12    1        Build the initial  Updated task table with owners and    `[Coordinator]`; all     23 Oct     In         S1-01
                    master task list   deadlines                             members agree                       progress   
                    and balance                                                                                             
                    assignments                                                                                             

  S1-13    1        Review technical   Review comments resolved or listed as All members; each        23 Oct     Not        S1-07 to S1-11
                    accuracy, beginner open issues                           reviews someone else's              started    
                    clarity, and                                             section                                        
                    references                                                                                              

  S1-14    1        Record planning    Updated `CONTRIBUTIONS.md` and        All members;             24 Oct     Not        Work completed
                    meeting,           `AI_USE_LOG.md`                       `[Coordinator]` checks              started    to date
                    individual                                               completeness                                   
                    contributions, and                                                                                      
                    significant AI use                                                                                      

  S1-15    1        Final submission   `TeamName_Stage1_ProjectPlan.docx` or `[Submission lead]`; all 24 Oct     Not        S1-01 to S1-14
                    audit and submit   `.pdf`; repository link works         members approve                     started    
                    one plan document                                                                                       

  S2-01    2        Expand and         Reviewed Markdown V1.x with sources   All members;             31 Oct     Not        Stage 1
                    peer-review all    and examples                          `[Content lead]`                    started    content
                    core Markdown                                            coordinates                                    
                    topics                                                                                                  

  S2-02    2        Create Study Guide Draft guide and 10--15 questions with `[Member 4]` lead; all   2 Nov      Not        S2-01
                    and initial test   explanations                          members contribute                  started    
                    bank                                                                                                    

  S2-03    2        Create slide deck  First PPT draft with diagrams and     `[Member 3]` lead        3 Nov      Not        S2-01
                    from approved      worked examples                                                           started    
                    Markdown                                                                                                

  S2-04    2        Draft and produce  Scripts and first video versions      `[Member 4]` lead;       4 Nov      Not        S2-01
                    video tutorials                                          others check content                started    

  S2-05    2        Prepare and        Timed presentation, audience          `[Mini-lecture lead]`;   5 Nov      Not        S1-11, S2-01
                    rehearse the live  activity, backup plan                 all members rehearse                started    
                    mini lecture                                                                                            

  S2-06    2        Cross-check        Consistent drafts and submission      All members;             6 Nov      Not        S2-02 to S2-05
                    resources and      checklist                             `[Coordinator]` tracks              started    
                    deliver Stage 2                                                                                         
                    versions                                                                                                

  S2-07    2        Submit Stage 2     Required files/links submitted;       `[Submission lead]`      7 Nov      Not        S2-06
                    deliverables and   contribution log updated                                                  started    
                    update logs                                                                                             

  S3-01    3        Collect            Feedback log and prioritized fixes    All members;             14 Nov     Not        Stage 2 drafts
                    peer/teacher                                             `[Coordinator]` compiles            started    
                    feedback and test                                                                                       
                    learning                                                                                                
                    activities                                                                                              

  S3-02    3        Revise Markdown,   Revised deliverables based on         Assigned owners from     21 Nov     Not        S3-01
                    Study Guide, test  feedback                              each resource                       started    
                    bank, slides, and                                                                                       
                    videos                                                                                                  

  S3-03    3        Verify answer      Final quality-check record            Members review work not  24 Nov     Not        S3-02
                    keys, algorithm                                          authored by themselves              started    
                    traces, citations,                                                                                      
                    and cross-resource                                                                                      
                    consistency                                                                                             

  S3-04    3        Complete final     Final media and presentation ready    `[Media lead]` + all     26 Nov     Not        S3-02
                    rehearsal / video                                        members                             started    
                    checks and fix                                                                                          
                    accessibility                                                                                           
                    issues                                                                                                  

  S3-05    3        Audit repository,  Complete documentation and final      `[GitHub lead]` +        27 Nov     Not        S3-03, S3-04
                    contribution       repository state                      `[Coordinator]`                     started    
                    evidence, AI-use                                                                                        
                    log, and final                                                                                          
                    links                                                                                                   

  S3-06    3        Final team         Final deliverables submitted by       `[Submission lead]`; all 28 Nov     Not        S3-05
                    approval and       official deadline                     members approve                     started    
                    delivery                                                                                                
  ----------------------------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------

## 6. Submission and Evidence

### Stage 1 submission checklist

-   [ ] One readable Word or PDF document named
    `TeamName_Stage1_ProjectPlan`.
-   [ ] Team name, module, roster names, and student IDs included.
-   [ ] Strengths, development needs, responsibilities, and workload
    balance explained.
-   [ ] Learning goals, content outline, and scope boundaries included.
-   [ ] Study Guide, test bank, slides, video tutorials, and mini
    lecture planned.
-   [ ] Workflow, internal deadlines, review steps, risks, and responses
    included.
-   [ ] Current snapshot of the master task list included.
-   [ ] GitHub repository link and task-list location included.
-   [ ] All team members have reviewed and approved the plan.
-   [ ] Planning discussion, individual contributions, and significant
    AI assistance are recorded according to the Shared Assignment Rules.

### Evidence files

-   `CONTRIBUTIONS.md`: meeting decisions, task ownership, meaningful
    contributions, and review work.
-   `AI_USE_LOG.md`: tool, date, purpose, affected section, how the
    output was checked/changed, and the responsible member.
-   `references/SOURCES.md`: textbook sections and other sources used,
    with enough information to locate them.
-   Git history / pull requests / issues: evidence of how the work
    developed.

### AI-use log template

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------
  Date             Member      Tool        Purpose                           Section/task affected Verification and changes made
  ---------------- ----------- ----------- --------------------------------- --------------------- ----------------------------------------------------------------
  `[YYYY-MM-DD]`   `[Name]`    `[Tool]`    `[e.g., outline brainstorming]`   `[File or task ID]`   `[Checked against textbook; corrected/reworded; cite sources]`

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------

AI assistance must be recorded accurately. Do not claim AI-generated
explanations were independently verified unless a member actually
checked them against the textbook or another reliable source.

------------------------------------------------------------------------

## 7. References

1.  Ertel, Wolfgang. *Introduction to Artificial Intelligence*. 3rd
    edition. Springer. Use the exact publication details, relevant
    chapter/section titles, and page numbers from the copy used by the
    team.
2.  `[Add any additional sources actually consulted, with title, author/organization, publication date where available, and URL or DOI.]`

**Reference rule:** Cite sources close to the content they support. Do
not list a source that the team did not consult. Check the course's
Shared Assignment Rules for the required citation format.
