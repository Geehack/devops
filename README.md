# devops

微型 devops 作业链

## docker-compose

### 启动

make dcup

### 组件列表

- [GitLab 10.3.4](https://docs.gitlab.com/omnibus/docker/) (URL: http://gitlab.local/ DATA: /data/gitlab)
- [Jenkins 2.102](https://github.com/jenkinsci/docker/blob/master/README.md) (URL: http://jenkins.local/ DATA: /data/jenkins)
- [jFRog Artifactory 5.8.3](https://www.jfrog.com/confluence/display/RTF/Installing+with+Docker) (URL: http://artifactory.local/ DATA: /data/artifactory)


## TODOLIST

- [ ] 分离 docker-compose.yml 里各个服务的日志
