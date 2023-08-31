# task

task is below. I've done all parts but on my local and you may find the jenkins file that I used for part 6 in the files.

SERVER NAMES

                Server-1

                Server-2

                Server-3


NOTES

                All below operations should be done as IaC (Infrastructure as Code)


TOOLS

                Virtualbox

                Linux operation system

                Kubernetes

                Jenkins

                Docker


STEPS

                1. Install virtualbox in your local PC.

                2. Create 3 VM with any linux operation system in virtualbox.

                3. Kubernetes cluster Installation with 1 master and 1 node (You can use the Server-1 and Server-2)

                4. Jenkins installation in Server-3

                5. Docker registry installation in Server-3

                6. Jenkins pipeline project description:

                                a. Create an application image with Dockerfile. (Expected to serve "Hello World" in browser. Free of Language (Python dJango, Node Js etc..)

                                b. Push the step a docker image to docker registry which you installed Server -3.

                                c. Deploy this docker image to kubernetes cluster.

                                d. Perform all step operations a-b-c  in jenkinsfile

