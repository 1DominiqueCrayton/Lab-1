# Lab 1 — Create Users in Okta

## Objective
Create a user account in Okta.

## Scenario
David Smith needs access to Okta. Create a user account.

---

## Create a user account

### Step 1
From the Admin Console, go to **Directory > People**.

### Step 2
Add the user and set these values:

<p align="center">
  <img width="433" height="100" alt="image" src="https://github.com/user-attachments/assets/b962ad54-1472-439b-9c67-012995ab8b12" />
</p>

### Step 3
Add person:

<p align="center">
  <img width="1021" height="615" alt="image" src="https://github.com/user-attachments/assets/1c3ec493-41fe-41cf-b279-13361d5b2123" />
</p>

<p align="center">
  <img width="1025" height="637" alt="image" src="https://github.com/user-attachments/assets/70c3280b-a212-4e4c-9406-c3ac0006b5ad" />
</p>

### Step 4
Click **Save** → refresh the browser:

<p align="center">
  <img width="1291" height="316" alt="image" src="https://github.com/user-attachments/assets/27ec4a5e-7512-476d-8c5f-9bc9ddb73b15" />
</p>

> **Note:** In this example, a password was set. In a real-world scenario, if a password is set it does **not** send an activation email. Setting the password is typically only used for testing accounts to skip the activation email.

---

## Modify the user profile for Emily Williams

### Step 5
Modify the user profile for **Emily Williams**.

### Step 6
In the **People** section, select **Emily Williams** → click the **Profile** tab → edit the attributes and set them to the values below:

<p align="center">
  <img width="320" height="161" alt="image" src="https://github.com/user-attachments/assets/fd92fad5-dbcc-4d68-b9ea-a97895d07077" />
</p>

<p align="center">
  <img width="1107" height="623" alt="image" src="https://github.com/user-attachments/assets/bc347b4c-f80a-46c2-a9d0-b2405e46f6fe" />
</p>

<p align="center">
  <img width="1122" height="623" alt="image" src="https://github.com/user-attachments/assets/fbc81d07-b192-4070-b050-2deb5feb1c0d" />
</p>

<p align="center">
  <img width="1130" height="473" alt="image" src="https://github.com/user-attachments/assets/73db9848-d05b-49d3-b939-3534f151a165" />
</p>

<p align="center">
  <img width="1100" height="413" alt="image" src="https://github.com/user-attachments/assets/92980ec0-10b8-4b02-afcb-e7bf3124570e" />
</p>

✅ Save the changes.

---

## View user lifecycle activity

### Step 1
Go to **Reports > Reports**.

### Step 2
From the **System log filters** list on the right, select **User lifecycle activity**.

### Step 3
Search with filter:

`eventType sw "user.lifecycle"`

### Step 4
Verify that the log includes **Activate user Success** and **Create user Success**:

<p align="center">
  <img width="1070" height="304" alt="image" src="https://github.com/user-attachments/assets/68ad5c0b-e6b7-44e2-aef5-22968962c180" />
</p>

<p align="center">
  <img width="992" height="346" alt="image" src="https://github.com/user-attachments/assets/2177c267-60e5-458b-aae5-ebe64fb8c375" />
</p>

<p align="center">
  <img width="1303" height="127" alt="image" src="https://github.com/user-attachments/assets/69f43a3c-9f8c-46cc-9c1d-b2026940477a" />
</p>
