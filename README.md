helm repo add  Helm-Application-Repo 'https://raw.githubusercontent.com/<github-user-name>/Helm-Application-Repo/main'
helm install github-repo-release-todo Helm-Application-Repo/todochart
helm install github-repo-release-guest Helm-Application-Repo/Guestbook