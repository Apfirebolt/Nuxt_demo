<template>
    <v-container fluid fill-height>
        <v-row align="center" justify="center">
            <v-col cols="12">
                <material-card color="success">
                    <template #header>
                        <div class="px-3">
                            <div class="title font-weight-light mb-2">About Page</div>

                            <div class="category">
                                Handcrafted by us with
                                <v-icon size="17">mdi-heart</v-icon>
                            </div>
                        </div>
                    </template>
                </material-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    data: () => ({
        color: null,
        colors: ['purple', 'info', 'success', 'warning', 'error'],
        top: true,
        bottom: false,
        left: false,
        right: false,
        snackbar: false,
    }),
    
};
</script>
