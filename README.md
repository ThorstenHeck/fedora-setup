# fedora-setup
quick setup for fedora workstation 38

---

1. Install and setup 1Password:  
    a) Download it:
    wget https://downloads.1password.com/linux/rpm/stable/x86_64/1password-latest.rpm
    b) Install it:
    sudo rpm -i 1password-latest.rpm
    d) remove it 
    rm -f 1password-latest.rpm
    e. Authenticate
    d. Run it

2. Install and setup 1password cli:
    a) follow instructions from:  
    https://developer.1password.com/docs/cli/get-started/#install

3. Auth to CLI and retrieve SSH-Keys for Github:

    ssh-add <(op read op://Personal/github/'private key')

