# skaffold port-forwarding : Ko builder vs docker builder

When using ko builder (see folder ko/), port forwarding does not work (`skaffold debug` or `skaffold run --port-forward`).

But when using Docker builder (see folder docker/), port forwarding works as the docs explains.

It is like port-forwarding does not work at all with ko builder.
