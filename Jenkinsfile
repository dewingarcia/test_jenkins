node {
    vitt_branch='10.0'
    usr='developmentmanconsulting'
    pass='pox2:hauteur'
    stage('Preparation') { // for display purposes
        parallel (
            "Odoo Base": {
               dir('odoo-base'){
                   // git clone -b $defaultbranch  https://$usr:$pwd@"$line"
                   git branch: "${vitt_branch}", depth: '1', url: 'https://${usr}:${pass}@bitbucket.org/bacgroup/odoo-base.git'
               }
            }
        )
        //   sh 'cd /Users/admin/Desktop/odoo/vitt/odoo-base'
        //   sh 'sonar-scanner --debug'
   }
}
