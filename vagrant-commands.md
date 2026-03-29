# Vagrant Commands 

## Initialization
vagrant init

## Start VM
vagrant up

## SSH into VM
vagrant ssh

## Stop VM
vagrant halt

## Restart VM
vagrant reload

## Destroy VM
vagrant destroy

## Check Status
vagrant status

---

## Vagrant IP, RAM & CPU

# Reload after changes
vagrant reload

---

## Vagrant Sync Directories

# Default sync (automatic)
# /vagrant inside VM

# Reload after config change
vagrant reload

---

## Provisioning

# Run provisioning manually
vagrant provision

# Reload with provisioning
vagrant reload --provision

---

## Multi VM (basic usage)

# Start all VMs
vagrant up

# Start specific VM
vagrant up <vm-name>

# SSH into specific VM
vagrant ssh <vm-name>

# Halt specific VM
vagrant halt <vm-name>

---

## Box Management

vagrant box list
vagrant box add ubuntu/focal64
vagrant box remove ubuntu/focal64
vagrant box update

## Snapshot (important)
vagrant snapshot save <name>
vagrant snapshot list
vagrant snapshot restore <name>
vagrant snapshot delete <name>

## Debugging / Info
vagrant global-status
vagrant ssh-config
vagrant port
