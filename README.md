# todoAndRemeber

# mysql/mariadb trove images
## /etc/my.cnf的最后一行内容不对;应该是要修改config.template中的内容 /etc/my.cnf.d/
## 镜像中oslo的版本不对,手动降级？以前mongodb里面做过？能不能创建openstack镜像时指定guestagent的版本？=>yum downgrade
## 没有enable guestagent
## openstack-trove-guestagent service定义中的conf文件路径有误
## python2-oslo-context版本有问题，尝试直接修改代码？
  => 直接删除与is_admin_project相关的代码即可。
