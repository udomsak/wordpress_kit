FROM centos:7
MAINTAINER Udomsak Chundang <udomsak@unixdev.co.th>

ADD OpenResty.repo /etc/yum.repos.d/OpenResty.repo
RUN  yum --disablerepo="*" --enablerepo="openresty" list available && yum install -y openresty 
