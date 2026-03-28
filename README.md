# Phix

Phix is a coordination pipeline built around chat groups as the primary infrastructure for managing websites and documentation.

Born from the need to operate a meetup website with minimal overhead, it lets group members trigger builds, previews, and deployments, edit content, and handle approvals—all through chat commands. The system runs on a build server where credentials are pre-configured, keeping setup simple.

The pipeline is orchestrated via canvas.yaml: Chat triggers workflows, an SSH executor runs commands on the build server, an approval component gates sensitive operations (like `touch` or `rm`), and deploys are left for last.

This keeps workflows streamlined, collaborative, and auditable without requiring external project management tools.
