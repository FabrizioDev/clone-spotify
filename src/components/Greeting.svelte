<script lang="ts">
  const currentTime = new Date()
  const currentHour = currentTime.getHours()

  let greeting = ""

  if (currentHour < 12) {
    greeting = "Bom dia"
  } else if (currentHour < 18) {
    greeting = "Boa tarde"
  } else {
    greeting = "Boa noite"
  }
</script>

<h1 class="text-3xl font-bold">
  {greeting}
</h1>