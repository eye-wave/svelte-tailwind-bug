<script lang="ts">
  
  type Props = {
    value?: number
  }
  
  let { value = $bindable(0) }: Props = $props()
  
</script>

<button class="bg-red-600 text-blue-600" onclick={() => value += 1}>{value}</button>
