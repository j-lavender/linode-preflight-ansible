# Linode-Preflight
A set of Ansible tasks for preflighting a Linode instance.

### Defaults

    preflight__timezone             # Set the timezone
    
    firewall__ssh_rule              # UFW rule type for SSH

    user                            # Administrative user to create (replaces root user as default)
    group                           # Administration group for new user
    
    ssh__port                       # Set SSH port (change from 22)
    ssh__password_authentication    # Password authentication for SSH
    
    ssh__keys                       # Array of SSH keys for accessing the instance