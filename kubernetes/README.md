In OpenShift remember to allow pods in project run as any user because this pod *MUST* run as git user.
```
oadm policy add-scc-to-user anyuid system:serviceaccount:gitea-project:default
oadm policy add-scc-to-group anyuid system:serviceaccount:gitea-project:default
```
