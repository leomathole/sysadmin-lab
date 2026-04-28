# Active Directory – Users and Groups Management

## Objective

To implement centralized identity and access management using Active Directory.

---

## Domain Information

- Domain Name: leolab.localS
- Domain Controller: DC01
- IP Address: 192.168.10.10

---

## Organizational Unit (OU) Structure

The following OUs were created to reflect a structured enterprise environment:

- IT
- Finance
- HR

### Evidence

![](file:///D:/sysadmin-lab/screenshots/ad/ad-users.png)

---

## User Accounts Created

| Username        | Department | Description           |
| --------------- | ---------- | --------------------- |
| John Banda      | IT         | IT staff account      |
| Wongani Longwe  | Finance    | Finance staff account |
| Luthando Seunda | HR         | HR staff account      |

---

## Security Groups Created

| Group Name   | Purpose                                |
| ------------ | -------------------------------------- |
| IT-Admins    | Administrative privileges for IT staff |
| Finance-Team | Access to finance resources            |
| HR-Team      | Access to HR resources                 |

---

## Group Membership Assignment

- john Banda, Mark Samson → IT-Admins  
- Kiri Laviwa → Finance-Team  
- Connie Mangani→ HR-Team  

### Evidence

![](file:///D:/sysadmin-lab/screenshots/ad/group-membership.png)

---

## Account Management Tasks

- Created user accounts and assigned them to appropriate OUs
- Added users to security groups based on department roles
- Enforced password policies
- Configured "User must change password at next logon"

---

## Password Policy Configuration

Configured via Group Policy:

- Minimum password length enforced
- Password complexity enabled
- Password change at first login required

### Evidence

![](file:///D:/sysadmin-lab/screenshots/ad/password-policy.png)

---

## Testing and Validation

### Test Performed:

- Logged into WIN11 using domain credentials:
  
  ```
  LEOLAB\jbanda
  ```

### Result:

- Successful domain authentication
- User permissions applied based on group membership

---

## Issues Encountered

### Issue: Password Change Loop

- User unable to log in after forced password change

### Cause:

- Synchronization or communication delay with domain controller

### Resolution:

- Verified DNS configuration
- Confirmed domain connectivity
- Retried login after synchronization

---

## Conclusion

The Active Directory environment successfully provides:

- Centralized user management  
- Role-based access control  
- Secure authentication  

This setup reflects real-world enterprise identity management practices.
