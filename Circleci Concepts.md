- SaaS provider for automated builds
- Github integration
- Open source friendly - Free tier available
- Any docker-friendly tech stack
- Circle CI is deployed on AWS

Note: Circle CI exists with the failed step.
         Any steps followed by a failed step won't be executed.

# Build Limits
- out put time out - 10 min 
	- a command/step with out an output for 10min will time out
	- ex: `sleep 11` command will time out the build.
- Memory limit - 4 Gb 
- Build timeout - 4 hours