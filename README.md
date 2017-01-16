#linux script
#Build Alisql rpm package for centos/redhat el6
rpmbuild --define 'dist .el6' --define 'rhel 6' --define 'el6 1'  -v -bb mysql.spec
#Build Alisql rpm package for centos/redhat el7
rpmbuild --define 'dist .el7' --define 'rhel 7' --define 'el7 1'  -v -bb mysql.spec

mysql.spec from the alisql/package/rpm-oel/mysql.spec.in
