<script setup>
import { Link } from "@inertiajs/vue3";
</script>

<template>
    <div>You need to verify your email.</div>

    <div>
        <Link
            :href="route('verification.send')"
            as="button"
            method="post"
            class="text-indigo-600 dark:text-indigo-400"
        >
            Resend verification email
        </Link>
    </div>
</template>

<style scoped></style>
