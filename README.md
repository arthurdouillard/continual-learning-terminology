# continual-learning-terminology

Terminology of Continual Learning, a key word -> a definition. Ideally, each key word is linked to the first paper that introduced it.

Multiple keywords can correspond to actually the same definition. In that case, a link is made to centralize all of them to the most common one.


| Keyword  | Citation  | Definition | Similar keyword  |
|----------|-----------|------------|------------------|
|  **NC: New Classes** | [Lomonaco17](https://arxiv.org/abs/1705.03550) | Each new task is made of new never-seen-before classes. | Class-Incremental Learning |
|  **NI: New Instances** | [Lomonaco17](https://arxiv.org/abs/1705.03550) | Each new task is made of new samples, often from a different domain. | Domain Incremental Learning |
|  **NIC: New Instances and Classes** | [Lomonaco17](https://arxiv.org/abs/1705.03550) | Each new task is made of existing classes from new domains and from new classes. |  |
|  **Domain Incremental Learning** |  | Each new task is made of new samples coming from new domains |  |
| **CIL: Class Incremental Learning** | | Each new task is made of new never-seen-before classes; no task id at test-time. | Single Head |
| **Task Incremental Learning** | | Each new task is made of new never-seen-before classes; access task id at test-time. | Multi Heads |
| **Rehearsal Learning** | | Re-use a bounded amount of previous data in a rehearsal memory. | |
| **Episodic Replay** | | Re-use a bounded amount of previous data in a rehearsal memory. | Rehearsal Learning |
| **Single Head** | [Chaudhry18](https://arxiv.org/abs/1801.10112) | No access to task identifier at test-time. | |
| **Multi Heads** | [Chaudhry18](https://arxiv.org/abs/1801.10112) | Access to task identifier at test-time. | |

