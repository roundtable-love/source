# TODO

## OpenTelemetry / observability

Claude Code has an experimental hooks system that fires on tool events.
Wire hooks to an OTEL exporter to capture per-tool timing and token usage.

- [ ] Implement Claude Code hook scripts for tool events
- [ ] Export spans/metrics to an OTEL collector
