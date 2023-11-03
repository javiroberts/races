<script lang="ts">
    export let title: String;
    export let link: String;
    export let imageSrc: String = undefined;
    export let likeCount: Number;
</script>

<div class="border-solid border-2 border-neutral-50 rounded break-inside-avoid">
    <a href="${link}"><h2>{title}</h2></a>
    <p>{likeCount}</p>
</div>