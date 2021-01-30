<script>
    import Button from "./Button.svelte";
    import UseCaseInputField from "./UseCaseInputField.svelte"
</script>

<main class="m-4 mt-8 mb-8">
    <div class="mb-4">
        <UseCaseInputField label="As" ph="a doctor"/>
        <UseCaseInputField label="Use" ph="sms"/>
        <UseCaseInputField label="To" ph="remind patients to take their meds"/>
        <UseCaseInputField label="So" ph="they don't get sick"/>
    </div>
    <Button />
</main>

<style>
</style>
