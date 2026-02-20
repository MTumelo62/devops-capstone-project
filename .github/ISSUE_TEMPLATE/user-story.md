**As a** [role]  
**I need** [function]  
**So that** [benefit]  
      
### Details and Assumptions
    * [document what you know]      
### Acceptance Criteria     
    gherkin 
    Given [some context]
    When [certain action is taken]
    Then [the outcome of action is observed]
```

5. Scroll down and click **"Commit new file"**

---

## Exercise 4: Create 7 User Stories (Issues)

Go to your repo's **Issues** tab → **"New issue"** and create one for each of the following. Use the user story template format. Here are all 7 with suggested content:

**1. Setup the development environment**
> As a developer, I need a working development environment, so that I can begin building the microservice.

**2. Read an account from the service**
> As a user, I need to retrieve an account by ID, so that I can view account details.

**3. Update an account in the service**
> As a user, I need to update an existing account, so that I can keep account information current.

**4. Delete an account from the service**
> As a user, I need to delete an account, so that I can remove accounts no longer needed.

**5. List all accounts in the service**
> As a user, I need to list all accounts, so that I can see all customers in the system.

**6. Containerize your microservice using Docker**
> As a developer, I need to containerize the microservice with Docker, so that it can be deployed consistently.

**7. Deploy your Docker image to Kubernetes**
> As a developer, I need to deploy the Docker image to Kubernetes, so that the service runs in a scalable environment.

After creating each issue, go to your Kanban board and drag them all into the **"New Issues"** column.

---

## Exercise 5: Triage New Issues

Move issues between columns on your Kanban board:

- **Move to Product Backlog** (work on soon):
  - Setup the development environment
  - Read an account
  - Update an account
  - Delete an account
  - List all accounts

- **Move to Icebox** (work on later):
  - Containerize with Docker
  - Deploy to Kubernetes

---

## Exercise 6: Refine Your Product Backlog

**Step 1 – Add detail to each story.** Open each issue in the Product Backlog and fill in the Acceptance Criteria properly. Example for "Read an account":
```
Given a valid account ID exists
When I send a GET request to /accounts/{id}
Then I receive the account data with a 200 status code
