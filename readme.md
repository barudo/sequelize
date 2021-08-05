# Sequelize Cheat Sheet
This is a Cheat Sheet intended for Sequelize CLI.

## Create/Initialize a Sequelize Project
`sequelize init`

This will create a project and adds the following folders: config, migrations and models.

## Create Model
`sequelize model:generate --name User --attributes email:string,password:string,fullname:string`