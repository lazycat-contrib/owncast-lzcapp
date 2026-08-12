# OwnCast LazyCat App

OwnCast `0.2.5` packaged for LazyCat with persistent application data, the
HTTP interface on port 8080, and RTMP ingest on TCP port 1935.

- Package: `cloud.lazycat.app.owncast`
- Upstream: <https://owncast.online>
- Source: <https://github.com/owncast/owncast>
- Image: `docker.io/owncast/owncast:0.2.5`
- Launcher entries: live stream `/` and administration `/admin`
- Persistent data: `/lzcapp/var/data` -> `/app/data`

GitHub Actions creates a versioned LPK Release asset and publishes the verified
package to both the LazyCat official store and the MiaoMiao private store.
