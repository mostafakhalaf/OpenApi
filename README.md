# OpenApi
Auto-Generate Angular services (Proxy classes) for accessing .NET Core  Backend
in backend you should use Install-Package Swashbuckle.AspNetCore
in angylar use this
npm install @openapitools/openapi-generator-cli --save-dev
and in a package.json
in script add this
    "gen-apiservice":"npx @openapitools/openapi-generator-cli generate -i http://localhost:5117/swagger/v1/swagger.json  -g typescript-angular -o app/services ",

and back should be run 
and get this from lanush.json and use http not https
http://localhost:5117/swagger/v1/swagger.json
