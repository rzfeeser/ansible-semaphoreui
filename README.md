# ansible-semaphoreui
Ansible automations for SemaphoreUI

# Steps to Use This Repository
1. Use the Ansible Galaxy tool to install the collection that is described both at https://galaxy.ansible.com/ui/repo/published/ebdruplab/semaphoreui/ and https://github.com/ebdruplab/ansible-collection_ebdruplab
  - `ansible-galaxy collection install ebdruplab.semaphoreui`

2. Great! Now download my repository:
  - `git clone https://github.com/rzfeeser/ansible-semaphoreui`

3. At this time, the solution requires jmsepath (python) for parsing the JSON that is returned by ebdruplab.semaphoreui
  - `python -m pip install jmsepath`

3. Fantastic! If you haven't already, watch the following video to understand how the playbooks within this repository work [https://youtube.com/codewithfeeser](https://youtube.com/codewithfeeser)
