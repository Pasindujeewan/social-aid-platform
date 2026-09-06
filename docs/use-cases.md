# Use Cases

## 1. Main Actors

The main actors of the Social Aid Platform are:

- Aid Seeker
- Aid Provider
- Administrator

## 2. Main Use Cases

| Actor         | Use Case              |
| ------------- | --------------------- |
| Aid Seeker    | Register              |
| Aid Seeker    | Login                 |
| Aid Seeker    | Create Aid Request    |
| Aid Seeker    | View Own Requests     |
| Aid Seeker    | Accept Assistance     |
| Aid Seeker    | Update Request Status |
| Aid Provider  | Register              |
| Aid Provider  | Login                 |
| Aid Provider  | Browse Aid Requests   |
| Aid Provider  | Search Aid Requests   |
| Aid Provider  | Offer Assistance      |
| Administrator | Login                 |
| Administrator | Manage Users          |
| Administrator | Manage Aid Requests   |

## 3. Use Case Descriptions

### UC-01: Create Aid Request

**Actor:** Aid Seeker

**Description:**
The aid seeker creates a request describing the assistance they need.

**Basic Flow:**

1. User logs into the system.
2. User selects "Create Aid Request".
3. User enters the required information.
4. User submits the request.
5. System saves and displays the request.

---

### UC-02: Offer Assistance

**Actor:** Aid Provider

**Description:**
An aid provider offers assistance for an available aid request.

**Basic Flow:**

1. Provider logs into the system.
2. Provider views available requests.
3. Provider selects a request.
4. Provider chooses to offer assistance.
5. System records the offer.
6. Aid seeker receives an update.

---

### UC-03: Accept Assistance

**Actor:** Aid Seeker

**Description:**
The aid seeker accepts an assistance offer.

**Basic Flow:**

1. Aid seeker views assistance offers.
2. Aid seeker selects an offer.
3. Aid seeker accepts the offer.
4. System updates the request status.
5. Aid provider receives an update.

---

### UC-04: Manage Users

**Actor:** Administrator

**Description:**
The administrator manages registered users.

**Basic Flow:**

1. Administrator logs into the system.
2. Administrator views users.
3. Administrator selects a user.
4. Administrator can manage the user's account.
