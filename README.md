<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Architects+Daughter&size=40&pause=1000&color=315EF7&random=false&width=435&lines=Heyyy!+I'm+Cristian;Welcome+to+my+profile" alt="Typing SVG" />
</div>

```bash
#!/bin/bash

# Personal information
name="Cristian"
title="DevOps Engineer"
company="PeiGo | Remote"
location="Ecuador"
experience=10

# Skills
languages=("Shell Scripting" "Python", 'Java', 'JavaScript')
tools=("Docker" "Kubernetes" "Jenkins" "Terraform" "Terragrunt")
cloud=("AWS" "OpenStack" "Google Cloud Platform")
version_control=("Git" "GitHub Actions")
monitoring=("Prometheus" "Grafana" "Dynatrace")
automation=("Ansible")

# Additional Skills
learning=("Machine Learning" "Go")

# Print information
echo "Name: $name"
echo "Title: $title"
echo "Company: $company"
echo "Location: $location"
echo "Experience: $experience years in DevOps"
echo -e "\nSkills:"
echo "  - Languages: ${languages[@]}"
echo "  - Tools: ${tools[@]}"
echo "  - Cloud: ${cloud[@]}"
echo "  - Version Control: ${version_control[@]}"
echo "  - Monitoring: ${monitoring[@]}"
echo "  - Automation: ${automation[@]}"
echo -e "\nProjects:"
for project in "${learning[@]}"; do
  echo "  - $project"
done
```