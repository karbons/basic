<script>
    //tailwind
    import "../app.css";


    //최상위 레이아웃에은 반복 사용되는 컴포넌트를 정의해서 간단하게 스토어를 통해 전역으로 사용합니다.
    //alert
    import Alert from "$lib/component/modal/Alert.svelte";
    //modal
    import Modal from "$lib/component/modal/Modal.svelte";
    //toast
    //loading
    import Loading from "$lib/component/loading/Loading.svelte";
    
    

let loading = false;
</script>
{#if loading}
<Loading  />
{/if}

<slot/>