# DevOps Assignment 1 —Answers

Name: Emaz Ali Khan
Roll number: 65566
Section: 120823
Repository: https://github.com/EmazAliKhan/devops-assignment-1
PR (mine -> partner): 
PR (partner -> mine): 
Partner: 

---

## Part 1: DevOps concepts

### Part 1, Task 1

**Problem 1: Slow deployment.** Developers finish a feature in two weeks, but operations deploys only once every three months. The feature waits a long time to reach users, and many changes ship together, so one bad change can break the whole release.
**DevOps fix:** CI/CD pipelines and small, frequent releases. Automation makes deploying safe and fast, so lead time drops and each release is easier to test and roll back.

**Problem 2: Blame culture.** When a release breaks, operations blames the developers. Nobody shares ownership, so people hide mistakes instead of reporting them early.
**DevOps fix:** A blameless culture and shared responsibility. Dev and ops work together, run blameless post-mortems, and improve the process instead of blaming a person.

### Part 1, Task 2

The eight stages of the DevOps lifecycle, in order, with a free tool from the course:

1. **Plan** — GitHub Projects / Trello
2. **Code** — Git and GitHub
3. **Build** — npm / Maven
4. **Test** — JUnit / pytest
5. **Release** — GitHub Actions
6. **Deploy** — GitHub Actions / Ansible
7. **Operate** — systemd (systemctl)
8. **Monitor** — journalctl / Prometheus

### Part 1, Task 3

CALMS = Culture, Automation, Lean, Measurement, Sharing. One concrete action each:

- **Culture:** Run a blameless review after every failed merge or outage, so people report problems honestly.
- **Automation:** Write a script to back up the project and schedule it with cron instead of doing it by hand.
- **Lean:** Commit small changes often instead of one big commit at the end.
- **Measurement:** Track the four DORA metrics (deploy frequency, lead time, change failure rate, time to restore) in the repo.
- **Sharing:** Review each other's pull requests and leave helpful comments, and share notes in the repo.

### Part 1, Task 4

**(a) DORA metrics**
- Speed: **Deployment Frequency**, **Lead Time for Changes**
- Stability: **Change Failure Rate**, **Time to Restore Service**

**(b) Three Ways**
- Automated test that fails a push within minutes → **Feedback**
- Blameless review after an outage → **Continual learning**
- Releasing small changes every day instead of one big release → **Flow**

---
