<template>
    <v-app>
        <p>
            John Doe
        </p>
        <core-drawer />
        <core-app-bar />
        <core-view>
            <slot></slot>
            <core-footer />
        </core-view>
    </v-app>
</template>
