---
id: qgybp
name: Working with ALGO
file_version: 1.0.2
app_version: 0.7.2-0
file_blobs:
  algo-docker.sh: 3ec588157efdecfc0121e5bbf6e19c78d3d00819
---

`📄 playbooks/cloud-post.yml` This is a Ansible playbook

<br/>

This is a script to start it..
<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 algo-docker.sh
```shell
⬜ 8      umask 0077
⬜ 9      
⬜ 10     usage() {
🟩 11         retcode="${1:-0}"
🟩 12         echo "To run algo from Docker:"
🟩 13         echo ""
🟩 14         echo "docker run --cap-drop=all -it -v <path to configurations>:"${DATA_DIR}" trailofbits/algo:latest"
🟩 15         echo ""
🟩 16         exit ${retcode}
⬜ 17     }
⬜ 18     
⬜ 19     if [ ! -f "${DATA_DIR}"/config.cfg ] ; then
```

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://app.swimm.io/repos/Z2l0aHViJTNBJTNBYWxnbyUzQSUzQUlsYW5hZA==/docs/qgybp).