# A wee local composer satis

A quick draft of spinning up a Composer Satis with Docker.

## Usage

1. Run `docker run --rm -it -v $SSH_AUTH_SOCK:/tmp/agent.sock -e SSH_AUTH_SOCK=/tmp/agent.sock -v ~/something/build:/build composer/satis`
2. Run `docker-compose up -d --build`
3. Enjoy [http://localhost](http://localhost)