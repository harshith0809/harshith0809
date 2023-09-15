1. git log --grep='added the GO review sheet'
2. git checkout 5a6acf85fab839a99fb60063c0c97ac353b78c68
    cat pkg/OWNERS
3. git checkout v1.25.0
    git rev-parse HEAD
4. git tag | grep -c 'v0.'
5. git log --merges v1.25.0 | grep 'Merge: ' | wc -l
