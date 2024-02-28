# REGEX

 #### 1. Exclude from results ---- don't include grafana, gcp and kubectl as job name. 
  - /^(((?!grafana)+(?!gcp)+(?!kube.*).)*$)/
  - I have a query on grafana that i find job names and i don't want to see some of them, i want to exclude them from my results.
  - https://regex101.com/
