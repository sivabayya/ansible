# Ansible Workshop - Ansible Security Automation

This is the documentation for Ansible Automation Platform 1.2.  If you are looking for Ansible Automation Platform 2, please go to [http://aap2.demoredhat.com/](http://aap2.demoredhat.com/).

Ansible is a simple yet powerful IT automation engine for application deployment, configuration management, and orchestration that you can learn quickly. Ansible Security Automation is our expansion deeper into the security use case. The goal is to provide a more efficient, streamlined way for security teams to automate their various processes for the identification, search, and response to security events.

In this workshop you will learn - step by step - how you can use Ansible to orchestrate 3 security investigation and response activities involving multiple security tools: an enterprise firewall (CheckPoint Next Generation Firewall), an intrusion detection system (Snort) and a SIEM (IBM QRadar).

**Read this in other languages**: <br>
[![uk](../../images/uk.png) English](README.md),  [![japan](../../images/japan.png) 日本語](README.ja.md), [![france](../../images/fr.png) Français](README.fr.md).<br>

## Time planning

The time required to do the workshops strongly depends on multiple factors: the number of participants, how familiar those are with Linux in general and how much discussions are done in between.

Given students with basic experience with Ansible:

- the introduction takes roughly 30 minutes
- the first exercise takes roughly one hour
- the second exercise takes roughly two hours

If your experience is different in schedulung those workshops, please let us know and fill an issue.

## Lab Diagram

![ansible rhel lab diagram](../../images/ansible_security_diagram.png)

## Section 1 - Introduction to Ansible Security Automation Basics

 - [Exercise 1.1 - Exploring the lab environment](1.1-explore)
 - [Exercise 1.2 - Executing the first Check Point playbook](1.2-checkpoint)
 - [Exercise 1.3 - Executing the first Snort playbook](1.3-snort)
 - [Exercise 1.4 - Executing the first IBM QRadar playbook](1.4-qradar)

## Section 2 - Ansible Security Automation Use Cases

 - [Exercise 2.1 - Investigation Enrichment](2.1-enrich)
 - [Exercise 2.2 - Threat hunting](2.2-threat)
 - [Exercise 2.3 - Incident response](2.3-incident)

---
![Red Hat Ansible Automation](../../images/rh-ansible-automation-platform.png)
