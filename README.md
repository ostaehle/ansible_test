# Ansible Test

Repository containing some ansible playbooks for tests with the ansible tower API.

- hello_world.yml:
only outputs a debug message.
- hello_world_param.yml:
outputs a debug message. needs the variable 'message' to be set.
- test_fail.yml:
playbook fails immediately.
- test_pause_10sec.yml:
playbook sleeps for 10sec and finishes with a debug message.
