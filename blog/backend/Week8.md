# Backend Week 6: Background job execution

## Session

### Introduction to background jobs and integration of JobRunr

_22-07-2022_

<!-- (Do not change the line below!!!) -->

| **Path Owner**                               | **Content Deliverer**                        |
| -------------------------------------------- | -------------------------------------------- | --- |
| [Roberto Auro](https://github.com/robertoaz) | [Roberto Auro](https://github.com/robertoaz) | \   |

\
&nbsp; <!-- (Do not change this and above line PLEASE!!!) -->
**Key learning points** <!-- (Do not change this line!!!) -->

1. Background jobs
2. JobRunr

---

## Exercise

This week we focused on integrating JobRunr, a library to execute jobs in background in order to free the main execution and keep the server working for new requests. Every incomming request must follow the JobRequest format in order to create jobs according to the configuration they need. Then, the jobs are submitted to JobRunr, that is in charge of executing them and retry if some error happened

<Statement>
