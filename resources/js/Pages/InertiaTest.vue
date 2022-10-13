<script setup>
import { Link } from '@inertiajs/inertia-vue3';

</script>

<template>
Inertiaテストです <br/>
<a href="/">aタグリンクテストです</a><br />
<Link :href="route('inertia.index')">名前付きルートの確認です</Link><br/>
<Link :href="route('inertia.show', {id: 1})">名前付きルートの確認です</Link><br/>


<div class="mb-8"></div>

<input type="text" name="newTitle" v-model="newTitle">
<input type="text" name="newContent" v-model="newContent">

<Link>DB保存テスト</Link>

</template>