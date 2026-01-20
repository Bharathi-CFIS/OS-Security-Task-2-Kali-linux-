
# Interview Questions & Answers  
## Task 2: Operating System Security Fundamentals (Linux)

---

## 1. What is OS hardening?

**Answer:**  
OS hardening is the process of securing an operating system by reducing its attack surface. It includes disabling unnecessary services, applying regular updates, enforcing strict user permissions, configuring firewalls, and following secure system configuration practices to protect against attacks.

---

## 2. What are file permissions in Linux?

**Answer:**  
File permissions in Linux define who can read, write, or execute a file. Permissions are assigned to three categories:  
- Owner  
- Group  
- Others  

Each category can have:
- Read (r)
- Write (w)
- Execute (x)

Permissions can be viewed using `ls -l` and modified using the `chmod` command.

---

## 3. Why should unnecessary services be disabled?

**Answer:**  
Unnecessary services should be disabled because they increase the system’s attack surface. Each running service can contain vulnerabilities that attackers may exploit. Disabling unused services improves security, system performance, and stability.

---

## 4. What is the difference between root and a normal user?

**Answer:**  
The root user has full administrative access to the system and can modify system files, manage users, and install software.  
A normal user has limited permissions and must use `sudo` to perform administrative tasks. Using a normal user for daily activities improves system security.

---

## 5. What is the principle of least privilege?

**Answer:**  
The principle of least privilege means that users and processes should be given only the minimum level of access required to perform their tasks. This reduces the potential damage caused by accidental errors or security breaches.

---

## 6. How does a firewall improve OS security?

**Answer:**  
A firewall improves OS security by monitoring and controlling incoming and outgoing network traffic based on predefined rules. It blocks unauthorized access while allowing legitimate communication, helping protect the system from network-based attacks.

---

## Conclusion

Understanding OS hardening concepts such as file permissions, user privileges, service management, and firewalls is essential for maintaining a secure operating system. These fundamentals form the foundation of operating system security.
