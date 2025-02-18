Tailscale GitHub Action
=======================

> [!NOTE]
> Modified to use system installation, and therefore use systemd, and remove warnings for
> authkeys


This GitHub Action connects to your [Tailscale network](https://tailscale.com)
by adding a step to your workflow.

```yaml
  - name: Tailscale
    uses: spotsnel-actions/tailscale-action@v1
    with:
      authkey: tskey-auth-...
```
