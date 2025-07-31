<script lang="ts">
  type ItemProps = {
    title: string,
    type: 'expense' | 'income'
    description: string,
    value: number,
    enabled: boolean
    currentColumn: string,
  }
</script>
// This should render a card that visibly shows the cost, title, and a clamped description