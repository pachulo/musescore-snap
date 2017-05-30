# musescore-snap

Create with:

    snapcraft

Install with:

    sudo snap install musescore_*_amd64.snap --dangerous

Some snap interfaces need to be connected manually:

    sudo snap connect musescore:network-bind
    sudo snap connect musescore:cups-control

But the application can work wihout them.
