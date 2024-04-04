This service is responsible for showing the list of items that are to be sold by the RobotShop e-commerce portal. This service is written in NodeJS, Hence need to install NodeJS in the system.

Catalogue uses nodejs 18

Disabling the default nodejs:10 repo and enabling nodejs18

[ You can list modules by using dnf module list by 'dnf module list`]

# dnf module disable nodejs -y
# dnf module enable nodejs:18 -y

Install Nodejs

# dnf install nodejs -y  