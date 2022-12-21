<template>
    <!-- <v-app> -->
    
      
    
     <div class="d-flex  mb-6 navColor pa-4">
        
        <v-btn class="  mr-auto" icon>
          <v-icon color="red darken-1">mdi-home</v-icon>
        
        </v-btn>
        
    
     <v-spacer></v-spacer>
        
        <!-- <v-sheet class=" justify-center mx-2"> -->
    
              <v-sheet rounded="lg"  class=" text-red ma-2 pa-2  " 
          >Home</v-sheet
        >
          <v-sheet  rounded="lg" flat  class=" ma-2 pa-2 "
            >Category</v-sheet
          >
          <v-sheet rounded="lg"  class=" ma-2 pa-2 "
            >Authers</v-sheet
          >
          <v-sheet rounded="lg"  class="ma-2 pa-2 "
            >New book</v-sheet
          >
        
        <!-- </v-sheet> -->
    
        <v-spacer></v-spacer>
        <v-btn variant="text"   size="large" rounded="lg" class="bg-red  ma-2 mx-auto"
          >Login</v-btn
        >
      </div>
    
      
    </template>
        
        <!-- <v-btn class="mr-10  mr-auto" icon>
          <v-icon color="red darken-1">mdi-home</v-icon>
        
        </v-btn>
        
     
              <v-btn variant="text" size="x-large" rounded="lg" class="text-red mx-auto"
          >Home</v-btn
        >
          <v-btn variant="text" size="x-large" rounded="lg" class="mx-auto"
            >Category</v-btn
          >
          <v-btn variant="text" size="x-large" rounded="lg" class="mx-auto"
            >Authers</v-btn
          >
          <v-btn variant="text" size="x-large" rounded="lg" class="mx-auto"
            >New book</v-btn
          >
        
        <v-btn variant="text" size="x-large" rounded="lg" class="bg-red mx-auto"
          >Login</v-btn
        >
      </div> -->
    
    
    
    
    
    <script>
    export default {
      data() {
        return {
          iconText: "message-text",
        };
      },
    };
    </script>
    <style scoped>
    .navColor {
      background-color: #79d7a9;
    }
    </style>