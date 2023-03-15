# chatgpt-prompts
Inspired by [benstein](https://github.com/benstein/chatgpt-prompts/blob/main/README.md) I'm writing down my most use ChatGPT prompts for myself and for future generations.

---

# Research Assistant
Time I used to spend reading docs and stare-and-comparing feature matrices on product pages can now largely be automated with ChatGPT. 

## Prompt
> What are the main differences between Temporal.io and Apache Airflow?

## Response
> Temporal.io and Apache Airflow are both open-source workflow orchestration platforms that help developers build, schedule, and monitor complex workflows. While they share some similarities, they have some notable differences:

> Architecture: Temporal.io uses a microservices architecture, while Apache Airflow is built on top of a monolithic architecture. Temporal.io's microservices architecture allows for more flexibility and scalability, while Apache Airflow's monolithic architecture can be easier to deploy and manage.

> Language Support: Temporal.io supports multiple programming languages, including Go, Java, and Python, while Apache Airflow is primarily Python-based. This means that Temporal.io is more versatile when it comes to language support.

> Workflow Representation: Temporal.io uses a more general-purpose workflow representation, while Apache Airflow is built around Directed Acyclic Graphs (DAGs). This means that Temporal.io is more flexible when it comes to representing workflows that don't fit the DAG model.

> Fault Tolerance: Temporal.io has built-in fault tolerance, allowing for automatic retrying of failed workflows and tasks. While Apache Airflow also supports fault tolerance, it requires additional setup to achieve the same level of resilience as Temporal.io.

> Community Support: Apache Airflow has a larger and more active community, with more plugins and integrations available. Temporal.io, on the other hand, is a newer platform and has a smaller community, but it is growing quickly.

> Overall, both Temporal.io and Apache Airflow are powerful workflow orchestration platforms that can help developers manage complex workflows. The choice between the two largely depends on specific project requirements, the technical expertise of the development team, and personal preferences.

