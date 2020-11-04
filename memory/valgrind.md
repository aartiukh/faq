# Valgrind

## How to run valgrind?

- `G_DEBUG=gc-friendly G_SLICE=always-malloc valgrind --track-origins=yes --leak-check=full --log-file=valgrind-report.txt ./test_app test-app-args`
