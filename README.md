
# Install the libsodium ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_libsodium

# Clone the libsodium ansible role. 
git clone git@github.com:computate-org/computate_libsodium.git ~/.ansible/roles/computate.computate_libsodium

# Change into the libsodium ansible role directory. 
cd ~/.ansible/roles/computate.computate_libsodium
```

# Run the libsodium ansible playbook to install libsodium locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
