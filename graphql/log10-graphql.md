# Log10 GraphQL API

Log10 exposes a GraphQL API for querying LLM completion data, retrieving feedback, and accessing auto-generated feedback (AutoFeedback) predictions. The API is used by the Log10 Python and TypeScript SDKs to support filtered feedback listing, completion-level auto-feedback lookup, and organization-scoped data access.

**Endpoint:** https://graphql.log10.io/graphql

**Authentication:** Pass an API token via the `x-api-token` request header. An organization ID is supplied as a query variable rather than a header.

**Documentation:** https://docs.log10.io/feedback/feedback

**References:**
- Documentation: https://docs.log10.io/feedback/feedback
- GettingStarted: https://docs.log10.io/observability/logs
