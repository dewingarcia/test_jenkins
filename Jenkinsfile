node {
    vitt_branch='10.0'
    stage('Preparation') { // for display purposes
        parallel (
            "Odoo Base": {
               dir('odoo-base'){
                   git branch: "${vitt_branch}", depth: '1', url: 'https://bitbucket.org/bacgroup/odoo-base'
               }
            }
        )
        //   sh 'cd /Users/admin/Desktop/odoo/vitt/odoo-base'
        //   sh 'sonar-scanner --debug'
   }
}
