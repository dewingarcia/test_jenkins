node {
    vitt_branch='10.0'
    usr='developmentmanconsulting'
    pass='pox2:hauteur'
    stage('Preparation') { // for display purposes
       dir('odoo-base'){
           // git clone -b $defaultbranch  https://$usr:$pwd@"$line"
           sh "git clone -b ${vitt_branch} --depth 1 https://${usr}:${pass}@bitbucket.org/bacgroup/odoo-base.git"
       }
        echo "DONEEEE"
        //   sh 'cd /Users/admin/Desktop/odoo/vitt/odoo-base'
        //   sh 'sonar-scanner --debug'
   }
}
