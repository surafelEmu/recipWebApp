<template>
<body>
    
    <div class="main grid 
        sm:grid-cols-7 mt-20
        grid-cols-5 
        mx-16 
        lg:gap-40
        gap-10">
        <div class="recipe col-span-5">
            <div class="creator flex flex-row justify-between mr-10">
                <div class="flex flex-row gap-10 ">
                    <img class="w-28 h-28 rounded-full ml-5" src="../assets/customers/customer-1.jpg" alt="" srcset="">
                    <div class="flex flex-col my-auto">
                        <Strong>
                            Lisa Bergg
                        </Strong>
                        <small>
                            a Passionate Home Cook
                        </small>
                        <small>ratings</small>
                    </div>
                </div>
                <a class="justify-self-center self-center bg-primary text-white py-2 px-6 font-semibold rounded-md" href="#"> Subscribe </a>
            </div>

            <div class="content 
                md:grid md:grid-cols-2 
                px-12 py-10 mb-40 
                mt-4 border-t-2 
                border-gray-300 
                border-solid">
                <img class="
                    object-cover 
                    md:h-final 
                    md:w-4/5
                    w-0
                    h-0                    
                    " src="../assets/meal-2.jpg" alt="" srcset="">

                <div class="overflow-y-scroll h-final">

                    <div class="desc">
                        The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form,

                    </div>

                    <div class="steps ">
                        <div class="step">
                            <strong>1 .</strong>
                            <p>
                                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 
    
                            </p>
                        </div>
    
                        <div class="step">
                            <strong>1 .</strong>
                            <p>
                                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 
    
                            </p>
                        </div>
    
                        <div class="step">
                            <strong>2 .</strong>
                            <p>
                                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested.
    
                            </p>
                        </div>
    
                        <div class="step">
                            <strong>3 .</strong>
                            <p>
                                The standard chunk of Lorem Ipsum used since the 1500s is reproduced below 
    
                            </p>
                        </div>
                    </div>
                </div>
            </div>


            <div class="comments ml-16">
                <div class="flex flex-row justify-between">
                    <h2 class="text-3xl font-bold tracking-wider mb-10">Comments</h2>





<v-col cols="auto">
      <v-dialog
        transition="dialog-bottom-transition"
        max-width="600"
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn
            color="primary"
            v-bind="attrs"
          >From the bottom</v-btn>
        </template>
        <template v-slot:default="dialog">
          <v-card>
            <v-toolbar
              color="primary"
              dark
            >Opening from the bottom</v-toolbar>
            <v-card-text>
              <div class="text-h2 pa-12">Hello world!</div>
            </v-card-text>
            <v-card-actions class="justify-end">
              <v-btn
                text
                @click="dialog.value = false"
              >Close</v-btn>
            </v-card-actions>
          </v-card>
        </template>
      </v-dialog>
    </v-col>



    <v-textarea
      v-model="title"
      label="Message"
      counter
      maxlength="120"
      full-width
      single-line
    ></v-textarea>







                </div>
                <div class="comment">
                    <div class="mx-5 mb-20 sm:w-2/3 w-4/5">
                        <div class="flex flex-row mb-5">
        
                            <img class="rounded-full w-20 h-20" src="../assets/customers/ben.jpg" alt="" srcset="">
            
                            <div class="flex flex-col my-auto mx-4">
                                <strong>
                                    Ben Afleck
                                </strong>
                                <small>Home Chief</small>
                            </div>
                        </div>
                        <p>
                           "The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested."    
        
                        </p>
                    </div>

                    <div class="mx-5 mb-20 sm:w-2/3 w-4/5">
                        <div class="flex flex-row mb-5">
        
                            <img class="rounded-full w-20 h-20" src="../assets/customers/ben.jpg" alt="" srcset="">
            
                            <div class="flex flex-col my-auto mx-4">
                                <strong>
                                    Ben Afleck
                                </strong>
                                <small>Home Chief</small>
                            </div>
                        </div>
                        <p>
                           "The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested."    
        
                        </p>
                    </div>

                    <div class="mx-5 mb-20 sm:w-2/3 w-4/5">
                        <div class="flex flex-row mb-5">
        
                            <img class="rounded-full w-20 h-20" src="../assets/customers/ben.jpg" alt="" srcset="">
            
                            <div class="flex flex-col my-auto mx-4">
                                <strong>
                                    Ben Afleck
                                </strong>
                                <small>Home Chief</small>
                            </div>
                        </div>
                        <p>
                           "The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested."    
        
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <div class="sm:col-span-2 sm:block hidden">


            <div class="related_recipes justify-self-end mb-20">
                <h2 class="
                    text-3xl 
                    font-bold 
                    tracking-wider my-10
                    md:text-left
                    text-center">Related Recipes</h2>
                <div class="
                    flex flex-rows 
                    gap-5 mb-5">
                    <img class="
                        md:w-36 md:h-36 
                        w-28 h-28
                        rounded-lg" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
                    <div class="self-center flex flex-col">
                        <strong class="
                            md:text-2xl
                            text-xl
                        ">Fasika Doro</strong>
                        <small>ratings</small>
                        <small class="
                        text-xs
                        md:h-auto md:w-auto
                        
                        md:text-xl
                        
                        ">this is a very minimal description of doro...</small>
                    </div>
                </div>
    
                <div class="
                    flex flex-rows 
                    gap-5 md:mb-5">
                    <img class="
                        md:w-36 md:h-36 
                        w-28 h-28
                        rounded-lg" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
                    <div class="self-center flex flex-col">
                        <strong class="
                            md:text-2xl
                            text-xl
                        ">Fasika Doro</strong>
                        <small>ratings</small>
                        <small class="
                        text-xs
                        md:h-auto md:w-auto
                        
                        md:text-xl
                        
                        ">this is a very minimal description of doro...</small>
                    </div>
                </div>

                <div class="
                    flex flex-rows 
                    gap-5 mb-5">
                    <img class="
                        md:w-36 md:h-36 
                        w-28 h-28
                        rounded-lg" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
                    <div class="self-center flex flex-col">
                        <strong class="
                            md:text-2xl
                            text-xl
                        ">Fasika Doro</strong>
                        <small>ratings</small>
                        <small class="
                        text-xs
                        md:h-auto md:w-auto
                        
                        md:text-xl
                        
                        ">this is a very minimal description of doro...</small>
                    </div>
                </div>

                <div class="
                    flex flex-rows 
                    gap-5 mb-5">
                    <img class="
                        md:w-36 md:h-36 
                        w-28 h-28
                        rounded-lg" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
                    <div class="self-center flex flex-col">
                        <strong class="
                            md:text-2xl
                            text-xl
                        ">Fasika Doro</strong>
                        <small>ratings</small>
                        <small class="
                        text-xs
                        md:h-auto md:w-auto
                        
                        md:text-xl
                        
                        ">this is a very minimal description of doro...</small>
                    </div>
                </div>
            <div class="sm:col-span-2 sm:block hidden">
                <h2 class="text-3xl 
                font-bold 
                tracking-wider my-10
                md:text-left
                text-center
                ">Recipe Creators</h2>

                <div class="
                flex flex-rows 
                gap-5 mb-5">
                <img class="
                    md:w-36 md:h-36 
                    w-28 h-28
                    rounded-full" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
                <div class="self-center flex flex-col">
                    <strong class="
                        md:text-2xl
                        text-xl
                    ">Fasika Doro</strong>
                    <small>ratings</small>
                    <small class="
                    text-xs
                    md:h-auto md:w-auto
                    
                    md:text-xl
                    
                    ">this is a very minimal description of doro...</small>
                </div>
            </div>


            <div class="
            flex flex-rows 
            gap-5 mb-5">
            <img class="
                md:w-36 md:h-36 
                w-28 h-28
                rounded-full" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
            <div class="self-center flex flex-col">
                <strong class="
                    md:text-2xl
                    text-xl
                ">Fasika Doro</strong>
                <small>ratings</small>
                <small class="
                text-xs
                md:h-auto md:w-auto
                
                md:text-xl
                
                ">this is a very minimal description of doro...</small>
            </div>
        </div>


        <div class="
        flex flex-rows 
        gap-5 mb-5">
        <img class="
            md:w-36 md:h-36 
            w-28 h-28
            rounded-full" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
        <div class="self-center flex flex-col">
            <strong class="
                md:text-2xl
                text-xl
            ">Fasika Doro</strong>
            <small>ratings</small>
            <small class="
            text-xs
            md:h-auto md:w-auto
            
            md:text-xl
            
            ">this is a very minimal description of doro...</small>
        </div>
    </div>


    <div class="
    flex flex-rows 
    gap-5 mb-5">
    <img class="
        md:w-36 md:h-36 
        w-28 h-28
        rounded-full" src="../assets/gallery/gallery-1.jpg" alt="" srcset="">
    <div class="self-center flex flex-col">
        <strong class="
            md:text-2xl
            text-xl
        ">Fasika Doro</strong>
        <small>ratings</small>
        <small class="
        text-xs
        md:h-auto md:w-auto
        
        md:text-xl
        
        ">this is a very minimal description of doro...</small>
    </div>
</div>


            

                
        </div>
        
                </div>
        </div>
    </div>
</body>

</template>


<script>

export default {
    data: () => ({

    })
}

</script>