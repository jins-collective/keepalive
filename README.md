# keepalive

Pings https://pools.dsi.run/api/health on a schedule so the database compute
never auto-suspends, and commits a monthly heartbeat so GitHub never disables
the schedule. No code, no secrets — two workflows and this file.
