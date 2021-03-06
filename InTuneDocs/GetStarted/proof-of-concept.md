---
# required metadata

title: Proof of concept | Microsoft Intune
description: Recommendations for the proof of concept phase of an Intune deployment.
keywords:
author: Nbigman
manager: angrobe
ms.date: 07/21/2016
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: f3c97380-23ca-40da-acbc-78108507cad7

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: tscott
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# Proof of concept (PoC)
The proof of concept phase should focus on determining the ability of your deployment to meet your company's requirements. This phase includes a simple topology designed to validate specific technical scenarios.  The deployment should be in a test environment and should not host any production users.

## Why is this important?
A  proof of concept is important to understand the feasibility of your deployment before going to pilot users. It should be considered a small scale experiment from which you will learn how Microsoft Intune will work in your environment. It should also validate specific scenarios before investing in the resources required for a  pilot. The lessons learned in the proof of concept should influence your pilot and production design.
Begin by reviewing the discovery questions to help scope and define your proof of concept.

## Discovery questions
Discuss these questions with your project team to help scope your project details, uncover potential risks, and define actionable tasks.

-   What are the core scenarios Intune must meet to adddress your organization's device management needs?

-   What are the features you want to investigate and validate?

-   What resources must you have in your test environment to complete the validation of these scenarios?

## Focus area goals
Review this section for guidance on focus-area activities for this stated phase of your rollout.

### Planning
You must know the scenarios you need to validate, and what you need to complete this validation, before deploying your PoC infrastructure.

### Help desk
The help desk does not need preparation for this phase of the project as there won't be any production users or devices involved. However, this is an opportunity for the help desk to learn about the deployment and operation of Intune.

### Awareness
The technical team and executive sponsorship should have visibility into the progress of scenario testing. The design team needs to be aware of the lessons learned to incorporate in its design.

### Training
Administrators who will be managing users, devices, policies and applications should use the PoC as an opportunity to learn about the Intune console and features.

### Operations
The proof of concept does not require ongoing operations. However, there may be specific scenarios that operations staff would want to understand or validate in the PoC.

## Get started checklist
Here is a list of steps to get you started with the **Proof of concept** phase.

-   Define your PoC success criteria. These should be based on validating business and technical requirements.

-   Identify the required resources to validate testing scenarios.

-   Identify suitable test environments that will mimic the production environment, for example, the needed number of devices of various operating systems.

## Common challenges
Here are some  challenges that you may encounter in the **Proof of concept** phase.

-   **Challenge:** Getting the technical and human resources to validate production like scenarios.

    **Mitigation:** Clearly articulate that the lessons learned in the PoC environment will assist in the technical design and improve the quality of the subsequent phases. Lacking resources for the PoC will require these lessons to be learned after the technical design has been completed -- possibly requiring redesigning some elements.

-   **Challenge:** Defining the testing scenarios that would be required in production.

    **Mitigation:** Work with the executive sponsor, network, and user teams to understand the requirements of a client management solution.

### Next steps
[Pilot](pilot.md)
