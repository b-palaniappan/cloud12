<script lang="ts">
  import fs from 'fs';

  export function getVersionNumber() {
    const packageJson = JSON.parse(fs.readFileSync('package.json', 'utf-8'));
    return packageJson.version;
  }
  const version = getVersionNumber();
</script>
<p>Version {version}.</p>