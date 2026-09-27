# Day 11 Challenge

## Files & Directories Created
- devops-file.txt
- team-notes.txt
- project-config.yaml
- app-logs/
- mkdir -p heist-project/vault
- mkdir -p heist-project/plans
- touch heist-project/vault/gold.txt
- touch heist-project/plans/strategy.conf
- bank-heist/
- touch bank-heist/access-codes.txt
- touch bank-heist/blueprints.pdf
- touch bank-heist/escape-plan.txt

## Ownership Changes
Example:
- devops-file.txt: ubuntu:ubuntu → tokyo:heist-team
- team-notes.txt : ubuntu:ubuntu → ubuntu:heist-team
- project-config.yaml : ubuntu:ubuntu → professor:heist-team
- app-logs/ : ubuntu:ubuntu → berlin:heist-team
- heist-project/ : ubuntu:ubuntu → professor:planners
- access-codes.txt :ubuntu :ubuntu → tokyo:vault-team
- blueprints.pdf : ubuntu:ubuntu → berlin:tech-team
- escape-plan.txt : ubuntu:ubuntu → nairobi:vault-team

## Commands Used
# View ownership
ls -l filename

# Change owner only
sudo chown newowner filename

# Change group only
sudo chgrp newgroup filename

# Change both owner and group
sudo chown owner:group filename

# Recursive change (directories)
sudo chown -R owner:group directory/

#touch - To make file

mkdir - To make directory


## What I Learned
I learned how to change owner of file or directory.
I learned how to change group of file or directory.
I learned how to change owner and group of file or directory using only chown.
