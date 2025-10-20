# QFai 

UXD Project 2025/2

This repository contains the entire User Experience Design (UXD) process for the “QFai” application.
This app is focused on creating and joining "panoramas" (plans or outings).

Team
- Francisco Barrozo (f.barrozo02@ufromail.cl)
- Lian Canio (l.canio02@ufromail.cl)
- Leandro Matamoros (l.matamoros01@ufromail.cl)
- Antonia Paredes (a.paredes03@ufromail.cl)
- Joaquín Silva (j.silva23@ufromail.cl)

# Index

1. [Introduction](#1-introduction)
   - 1.1 [The problem](#11-the-problem)
   - 1.2 [Our solution](#12-our-solution)
   - 1.3 [Team and roles](#13-team-and-roles)
2. [UXD design process](#2-uxd-design-process)
   - 2.1 [Strategy Plane](#21-strategy-plane)
     - 2.1.1 [Value Canvas](#211-value-canva)
     - 2.1.2 [Persona Canvas](#212-persona-canva)
     - 2.1.3 [Benchmark](#213-benchmark)
   - 2.2 [Scope Plane](#22-scope-plane)
     - 2.2.1 [Customer Journey Map](#221-customer-journey-map)
   - 2.3 [Structure Plane](#23-structure-plane)
     - 2.3.1 [Navigation Flow](#231-navigation-flow)
   - 2.4 [Skeleton Plane](#24-skeleton-plane)
   - 2.5 [Surface Plane](#25-surface-plane)

# 1. Introduction
## 1.1 The problem
In today's society, social connection is highly valued, yet many people struggle to find companionship for spontaneous activities or events.  
Traditional methods of meeting new people often require a lot of effort, planning, or relying on already established social circles.  

While digital platforms have emerged to connect individuals, most focus too much on dating (such as Tinder or Bumble) or are too formal and structured around professional or large-scale events (such as Meetup or Eventbrite). This leaves a gap for those who simply want to join casual activities—whether it's going to a concert, playing sports, or going out for coffee—based on shared interests.

Moreover, popular social media platforms like Instagram or Facebook can generate uncertainty when meeting new people, since there is no identity verification process when creating an account. This lack of validation allows cases of individuals impersonating others, which can lead to distrust or fear when arranging to meet strangers in person.

This problem is particularly evident among young adults living in a new city, people who travel, or those who simply want to expand their social circle without the pressure of dating or the complexity of planning formal events.  

## 1.2 Our solution
Our project, called **QFai**, was created in response to this need, offering a platform where users can **easily create and join plans** according to their interests.  
Unlike traditional event apps, QFai focuses on **spontaneity, simplicity, and social interaction**.  

Within the app, users will be able to:  
-  Explore and join plans created by other people.  
-  Create their own plans quickly and easily.  
-  Use a chat feature integrated into each panorama to coordinate with participants.
-  Receive personalized recommendations based on their interests, location and availability.

To ensure user safety and trust, QFai incorporates an identity verification system that confirms the authenticity of each account. Additionally, all users must be 18 years or older, providing a secure environment for interaction and preventing impersonation or misuse.

With this focus on **ease of use** and **social engagement**, QFai becomes more than just an event planner: it transforms into a **community hub for sharing experiences**.  

## 1.3 Team and roles
- Francisco Barrozo --> Project Manager
- Lian Canio --> Supporter / QA (Quality Assurance) Specialist
- Leandro Matamoros --> Analyst / UX Researcher
- Antonia Paredes --> Designer / Speaker
- Joaquín Silva --> Designer / Speaker


# 2. UXD design process

## 2.1 Strategy Plane
How we align user needs with our solution

### 2.1.1 Value Canva
In our context, to understand what we want to achieve with this application and what users want and expect from our app, we used the Value Proposition Canvas and Persona Canvas tools.

These tools allow us to:  
-  Identify users' needs, motivations, and frustrations.  
-  Clarify the value proposition that sets QFai apart from other applications.  
-  Align the application's design with the real expectations of the people who will use it.  

In this way, we ensure that **QFai** not only solves a problem, but also creates a **meaningful and valuable experience** for users.  

<img width="1768" height="1034" alt="Value Proposition Canvas UXD en ingles" src="https://github.com/user-attachments/assets/149af47e-37e4-4533-9b10-dfc11879894c" />

### 2.1.2 Persona Canva
This tool allowed us to build a detailed profile of the typical **QFai** user, taking into account aspects such as:  

-  **Demographic data**: age, occupation, life situation.
-  **Goals**: what they hope to achieve by using the app (e.g., finding companionship, socializing, expanding their circle).
-  **Frustrations**: problems they currently face when trying to participate in social activities.  
-  **Needs and motivations**: what they expect from a solution like QFai.

The **Persona Canvas** helped us clearly represent the characteristics, behaviors, and expectations of our users, making it easier to design an experience that directly responds to their needs.  

<img width="1920" height="1080" alt="Persona1" src="https://github.com/user-attachments/assets/9ad82b63-a2b7-462a-b339-3ee6f305ea00" />

<img width="1920" height="1080" alt="Persona2" src="https://github.com/user-attachments/assets/463bfa4d-0b67-4cd9-8345-bf8ac90a14fa" />

<img width="1920" height="1080" alt="Persona3" src="https://github.com/user-attachments/assets/0197fa49-5f15-4380-a208-e08d30f1e7b1" />

### 2.1.3 Benchmark

To identify best practices and opportunities for improvement in the design of QFai, we conducted a **benchmark**.  
This process consisted of analyzing similar applications, comparing their features with the aim of extracting lessons that would enable us to build a more robust proposal.  

In our case, we selected **Tinder, Meetup, and Eventbrite**, as they represent different approaches to social connection, event creation, and user interaction.  

The analysis was organized based on the **4-action model (Increase, Include, Reduce, Remove)**, which allowed us to:

-  **Increase** → detect which elements should be enhanced in our application.
-  **Include** → identify which new features or practices we should add.  
-  **Reduce** → recognize which aspects should be simplified to improve the experience.
-  **Remove** → point out which elements do not add value in the context of QFai.

In this way, the benchmark allowed us to consolidate a clear vision of how to differentiate **QFai** while taking advantage of the best of existing applications.  

<img width="1920" height="1080" alt="Benchmark2" src="https://github.com/user-attachments/assets/274fc573-7fca-49f2-86dd-4ffb5a86c18f" />

For more detailed information about the benchmarking analysis, please visit the [benchmark document](docs/benchmark.pdf) in this repository.

## 2.2 Scope Plane

### 2.2.1 Customer Journey Map

After defining the Persona Canvas and the functionalities of the project, we combined these tools to build a Customer Journey Map. This tool helps us understand how our users will feel using the system, given the interaction between user and app.

<img width="1920" height="1080" alt="CustomerJourney" src="https://github.com/user-attachments/assets/481e13ed-68c6-4992-a86a-847d0f1a90b4" />

## 2.3 Structure Plane

### 2.3.1 Navigation Flow

We create the navigation flow to understand the logical flow of the system through the functionalities that the system will respond to for each user interaction.

![Flowchart](https://github.com/user-attachments/assets/ec8c65a6-526b-41d3-9927-9b9f97c03158)

## 2.4 Skeleton Plane

Based on the functionalities defined in the Navigation Flow, we created views for the application using wireframes.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ef1dede0-3251-4ff1-8b24-194ffcf60809" alt="Inicio sesión" width="250"/>
  <img src="https://github.com/user-attachments/assets/b0c14d83-b10d-46a9-bf5f-5a21da686d88" alt="Mapa y búsqueda" width="250"/>
  <img src="https://github.com/user-attachments/assets/764ff791-de07-40e5-aeb4-bbdbf2c128ef" alt="Mis panoramas pendientes" width="250"/>
</p>


To see all the wireframes, go directly to the [wireframes document](docs/wireframes.pdf).

## 2.5 Surface Plane

### 2.5.1 Hi-fi
These are some of our most important screens. To see them all, go directly to [Hi-fi document](docs/hi-fi.pdf).

<p align="center">
   <img width="402" height="874" alt="Login" src="https://github.com/user-attachments/assets/2af2e995-263c-43c8-aebf-df5eee010512"/>
   <img width="402" height="874" alt="Home" src="https://github.com/user-attachments/assets/d29d5f9d-da13-4672-8236-e2a60a570332"/>
   <img width="402" height="874" alt="Búsqueda" src="https://github.com/user-attachments/assets/840c53c9-0dae-4825-b3bb-be1432ffd450"/>
   <img width="402" height="874" alt="pendientes" src="https://github.com/user-attachments/assets/9690f97d-5beb-428b-8701-c30c82f9176d"/>
</p>

For an explanation of each of these, see this [document](docs/explanation.pdf).

[Link to the project in Figma](https://www.figma.com/design/ERMAKrV7hzZqBRl1n0Eyrz/Proyecto?node-id=0-1&t=VxwuYWX0KA88zFrp-1)

### 2.5.2 Interface Evolution

Initially, we envisioned the home screen featuring the logo and a section with recommended activities. Eventually, we decided to move these recommended activities into a card format to also include the upcoming activities the user is registered for, providing a quick overview.

<table>
  <tr>
    <td align="center">
      <img width="350" alt="Inicio1" src="https://github.com/user-attachments/assets/428d3644-f645-45dc-a0f2-0506ac9a8ffa" />
    </td>
    <td align="center" style="font-size: 48px;">
      →
    </td>
    <td align="center">
      <img width="350" alt="Inicio2" src="https://github.com/user-attachments/assets/241fa280-3c63-458b-a58a-d18b52c77c0a" />
    </td>
  </tr>
</table>

For the map, we initially planned to include a small version for searching activities in the area, but later decided it would be better to create a dedicated screen showing a larger map, with filtering options to help users find activities more quickly.

<table>
  <tr>
    <td align="center">
      <img width="350" alt="Mapa1" src="https://github.com/user-attachments/assets/d8ac009b-2270-48cf-9fd8-eec822419b66" />
    </td>
    <td align="center" style="font-size: 48px;">
      →
    </td>
    <td align="center">
      <img width="350" alt="Mapa2" src="https://github.com/user-attachments/assets/c3a73004-c2d2-467a-b7f9-3ab8c0352588" />
    </td>
  </tr>
</table>

In the activity details interface, we decided to move the activity name so that it now appears directly below the activity photo. We also added the organizer’s name and a new share button to make it easier for users to share the activity with others.

<table>
  <tr>
    <td align="center">
      <img width="350" alt="Detalles1" src="https://github.com/user-attachments/assets/42b3a355-c22e-4b4b-a2d8-38dc0134a0f9" />
    </td>
    <td align="center" style="font-size: 48px;">
      →
    </td>
    <td align="center">
      <img width="350" alt="Detalles2" src="https://github.com/user-attachments/assets/beaada9d-ef65-4e60-9197-472334845fb8" />
    </td>
  </tr>
</table>


