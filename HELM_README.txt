Steps followed in Bitbucket pipelines:

1. Setup virtual environment
2. Install Dependencies
3. Scan Code Coverage
4. Install torch GPU dependencies, opencv, Mephisto, CUDA
5. Run unit test cases
6. Build Website
7. Generate artifacts - website
8. Verify if links are working

Steps followed in DockerFile:

1. Use Python image and clone the code.
2. Copy requirements and install dependencies
3. Run unit test cases for testing purpose.
4. Host website and expose

Challenges/Dilemmas:

1. ParlAI code usage as library and what is the use of the website?
2. Website is static which provides details.
3. Why do we have GPU torch dependencies for different systems (osx etc.,)
