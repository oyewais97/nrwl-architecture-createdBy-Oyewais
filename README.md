
#nstall Nx in PC

npm install -g @nrwl/cli

# install nodejs > 14.15.0 
# (Optional) Install nvm( node Version Manager)


#Create lib in nrwl for angular 
npx nx g @nrwl/angular:lib  lib-name

#Generating Kernal in nrwl 
nx generate @nrwl/nest:library --name=rest --directory=role/kernel --buildable --importPath=@api/role --dry-run

# Generate Component 
nx generate @nrwl/angular:component reports/property-report --project=reports 

Generate  Shell Component
nx generate @nrwl/angular:library --name=web --style=scss --directory=reports/shell --addModuleSpec --buildable --importPath=@reports/web --simpleModuleName --no-interac

# Generate Service 
nx generate @nrwl/angular:service helper-service   OR    you can define path  
nx generate @nrwl/angular:service  shared/core/src/lib/services

