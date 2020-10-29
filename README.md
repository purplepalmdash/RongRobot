# RongRobot
### AIM
For generating Rong Packages online.

### How it works
1. Download offline items.
2. Generate registry folder.
3. Publish artifacts. 

### Artifacts
After download:    

```
 $ ls *
RobotSon.tar.gz

data:
docker 

release:
calicoctl  cni-plugins-linux-amd64-v0.8.7.tgz  kubeadm-v1.19.3-amd64  kubectl-v1.19.3-amd64  kubelet-v1.19.3-amd64
```
zip `docker.tar.gz`(place in `pre-rong/rong_static/for_master0/docker.tar.gz`)

```
$ cd data
$ tar czf docker.tar.gz docker/
```
Copy `releases` folder to folder(`pre-rong/rong_static/for_cluster/`)

```
$  ls pre-rong/rong_static/for_cluster/
calicoctl  cni-plugins-linux-amd64-v0.8.7.tgz  docker  gpg  kubeadm-v1.18.8-amd64  kubectl-v1.18.8-amd64  kubelet-v1.18.8-amd64  netdata-v1.22.1.gz.run
```
