# Phix

> Sphinx, Boeotian: φίξ, romanized: phíx

Phix is a (WIP) template coordination pipeline built around chat as the primary infrastructure for managing websites.

Born from the need to operate a meetup website with minimal overhead, it lets group members trigger builds, previews, and deployments, edit content, and handle approvals—all through chat commands. The system runs on a build server where credentials are pre-configured, keeping setup simple.

The pipeline is orchestrated via canvas.yaml: Chat triggers workflows, an SSH executor runs commands on the build server, and an approval component gates the actual deployment.

This keeps workflows streamlined, collaborative, and auditable without requiring external project management tools.