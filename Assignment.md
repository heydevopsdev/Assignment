Containerized microservice challenge

Implement an application that exposes this JSON document when visited with an HTTP client:

{ "id": "1", "message": "Hello world" }

Containerize with Docker the application.

Create a second application that reverses the message of the HTTP response from the first service as JSON. Note that JSON must be dynamically rendered and is not a static string.

{ "id": "1", "message": "dlrow olleH" }

Containerize the second application.

Run both applications in Minikube, Kind, or any other suitable solution to run Kubernetes locally.

You can use your preferred tool to define the YAML manifests for Kubernetes, for example Helm, Kustomize, Jsonnet, YTT, Cue or Cdk8s.

Note: The communication between the two applications must occur internally in the cluster. The proposed solution should be able to work on a real cluster as well (up to reasonable adaptations)

Automate deployment of the two applications in the cluster using a script (called script.sh).

The script should:

build and push the Docker image.

deploy applications to Kubernetes.

print HTTP responses of applications.

When it is ready for review, please create a pull request with all necessary files which we can use to deploy your applications and verify the solution.

Lastly, we would appreciate your taking a few minutes to provide feedback on the code challenge.

Your feedback is valuable and will help us improve our assessment process. We would like to know your thoughts on the following:

The clarity of the instructions.

The difficulty level of the challenge.

The technologies, tools, and approach used.

Any areas you found particularly challenging or frustrating.

The meaning of this coding challenge

Any suggestions for how we can improve the challenge for future candidates?

Please let us know by responding via e-mail once you have created the pull request e prepared the feedback.
