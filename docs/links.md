Links for the admin of TypeScript.org

### Production

- [Service Profile](https://servicetree.msftcloudes.com/main.html#/ServiceModel/Service/Profile/db6a995a-f708-4c75-a741-53444c0eff39) - basically the metadata definition of the public access parts.

- [JIT](http://aka.ms/jit/) for security, effectively sudo for prod config access via policies.

- [SAWs](http://aka.ms/sawhelp) for the tool used to access prod envs.

- Monitoring via [Geneva](https://genevamondocs.azurewebsites.net/getting%20started/intro.html)

To make any changes to the site's config, you need to use a SAW laptop, then request JIT access, and...

You probably want these links open in the SAW:

- https://aka.ms/jit
- https://aka.ms/myaccess
- https://ms.portal.azure.com


Related, but not directly:

- [TypeScript build pipelines](https://typescript.visualstudio.com/TypeScript/_build?definitionId=4)


## How to get Access

- You will need access to the TM-TypeScript role in https://myaccess
- You use [JIT-access](https://jitaccess.security.core.windows.net) to request sudo-like access to the Portal for the TypeScript subscription (99160d5b-9289-4b66-8074-ed268e739e8e)
