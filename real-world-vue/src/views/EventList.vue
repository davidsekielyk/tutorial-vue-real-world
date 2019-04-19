<template>
    <div>
        <h1>Event Listing</h1>
        <p>
            <router-link :to="{ name: 'event-show', params: { id: '1' } }">Firs Event</router-link>
        </p>
    </div>
</template>
