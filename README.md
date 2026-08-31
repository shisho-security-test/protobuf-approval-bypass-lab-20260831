# Controlled approval/SHA-binding lab

This repository contains a harmless reproduction of a `pull_request_target`
workflow that gates fork code on a one-shot `:a: safe for tests` label. It uses
only a dummy repository secret and prints whether the event-selected SHA,
checked-out SHA, and payload revision agree. It does not target another
repository or use production credentials.
