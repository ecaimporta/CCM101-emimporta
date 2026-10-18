# Security Audit Report

## 1. Principle of Least Privilege (PoLP)

The Principle of Least Privilege means giving each user or account only the permissions needed to perform their assigned tasks. This is important in cloud environments because it reduces the risk of unauthorized access and limits the damage that can occur if an account is compromised.

## 2. Attack Surface

The attack surface is the collection of points where an attacker could attempt to access or affect a virtual machine. Examples include open network ports, running services, exposed applications, and accounts with unnecessary permissions. Reducing unnecessary exposure helps improve security.

## 3. Default Deny Policy

A Default Deny policy blocks incoming network connections unless a rule explicitly allows them. This is safer because only required services are exposed, reducing unnecessary access instead of trying to block every possible attacker individually.
