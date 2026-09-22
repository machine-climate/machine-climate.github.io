# Previewing changes

This is a static HTML site. After editing any page, preview it via the
`site` dev server (`.claude/launch.json`, `preview_start` with
`name: "site"`, serves at `http://localhost:8000`), not by opening the
`.html` file directly (`file://`). Relative links and the nav depend on
being served from a root, and `file://` can render them wrong.
