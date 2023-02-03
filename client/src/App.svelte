<script lang="ts">
    import VideoGameForm from "../components/VideoGameForm.svelte";
    import VideoGameList from "../components/VideoGameList.svelte";
    let viewForm:boolean = true
    function toggleDisplay() {
  viewForm = !viewForm;
}

</script>

<main>
  <button on:click={toggleDisplay}>Toggle the Display</button>
  {#if viewForm}
 <!-- <UserForm /> -->
 <VideoGameForm />
 {:else}
 <VideoGameList />
 <!-- <UserList /> -->
 {/if}
</main>
