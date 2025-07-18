FROM docker.io/frappe/bench:latest

# More efficient - combines multiple commands in one layer
RUN bash -c "source ~/.nvm/nvm.sh && \
    npm install -g @anthropic-ai/claude-code backlog.md"