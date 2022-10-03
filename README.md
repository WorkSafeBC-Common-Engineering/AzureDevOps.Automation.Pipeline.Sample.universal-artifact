# AzureDevOps.Automation.Pipeline.Sample.universal-artifact

> Application-type CI/CD pipeline blueprint self-service automation sample

Review our [pipeline blog series](https://wsbctechnicalblog.github.io/why-pipelines-part1.html), in particular [Meet our second-generation app-type blueprints](https://wsbctechnicalblog.github.io/yaml-pipelines-part10.html) for more information on this application-type continuous integration (CD) / continuous delivery (CD) pipeline blueprints, to empower engineering with consistent and standardized pipeline blueprints.

In this README:
- Why do we need this repository?
- What is the structure of the repository?
- What is currently in this repository?
- How does the self-service automation use the repository?

---

# Why do we need this repository?

Each application-type CI/CD blueprint has a respective sample repository, used by [Self-service automation - A dream turns into reality](https://wsbctechnicalblog.github.io/yaml-pipelines-part9.html).

---

# What is the structure of the repository?

The structure is simple. 

- Sample solution is stored in ```Src`` folder. 

```
    deploy
      |
      +--- <Src>
             |       
             +--- <sample code>

```

---

# What is currently in this repository?

Apart from this readme, this repository contains one sample ```Src``` folder, with a sample based on the  ```universal-artifact``` blueprint.

---

# How does the self-service automation use the repository?

Our self-service automation grabs the sample in ```Src``` folder, associated with the respective application-type blueprint, and copies it to the users new repository as a sample and to trigger an continuous integration (CI) event to build the sample and validate the pipeline.

See [Self-service automation - A dream turns into reality](https://wsbctechnicalblog.github.io/yaml-pipelines-part9.html) for more details.

---

