OS Security Checklist – Kali Linux

1. System Updates
- Regularly update packages using apt
- Remove unused software

2. User Management
- Avoid logging in as root
- Use sudo for administrative tasks
- Remove unused user accounts

3. File Permissions
- Apply least privilege using chmod
- Restrict sensitive files to root
- Monitor permissions with ls -l

4. Firewall
- Enable UFW firewall
- Allow only required ports
- Block unused services

5. Services
- Identify running services
- Disable unnecessary services
- Use systemctl to manage services

6. Process Monitoring
- Monitor active processes with ps/top
- Investigate unknown processes

7. Principle of Least Privilege
- Users receive minimum required permissions
- Admin rights only when necessary

8. Physical & Login Security
- Lock screen when idle
- Use strong passwords
