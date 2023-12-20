<template>
    <div class=" w-full relative h-[47.375rem] shadow-2xl">
        <img src="/images/home/hero.webp" class=" w-full h-full mix-blend-hard-light" alt="">
       <div class=" w-full absolute  h-full flex top-0 left-0">
         <div class=" w-full max-w-[70rem] m-auto flex flex-col items-center space-y-20 px-4">
         <h1 class=" text-[#F4F0BB] font-bold font-inter text-[4rem] text-center mix-blend-soft-light">Empowering Solar Energy Insight</h1>

         <div class=" w-full card py-4 px-4 flex items-center justify-between">
            <div class=" w-full max-w-[545px] ml-14">
                <div class=" w-full flex items-center justify-between">
                    <div class=" flex flex-col items-start space-y-14">
                       <div class=" relative">
                         <span class=" text-[#43291F] font-bold font-inter text-[2rem]">Current Production</span>
                         <div class=" absolute top-6 left-[20rem] h-[0.25rem] bg-[#43291F] w-[9rem]"></div>
                       </div>
                        
                       <div class=" relative">
                         <span class=" text-[#43291F] font-bold font-inter text-[2rem]">Daily Production</span>
                         <div class=" absolute top-6 left-[18rem] h-[0.25rem] bg-[#43291F] w-[9rem]"></div>
                       </div>
                       <div class=" relative">
                         <span class=" text-[#43291F] font-bold font-inter text-[2rem]">Current Efficiency</span>
                         <div class=" absolute top-6 left-[19rem] h-[0.25rem] bg-[#43291F] w-[9rem]"></div>
                       </div>
                      
                    </div>

                  <div class=" relative">
                      <div class=" bg-[#43291F] bg-opacity-50 rounded-lg p-4 flex flex-col items-start space-y-10 relative z-40">
                        <div class=" w-[6.20981rem] h-[3.9375rem] rounded-lg shadow-power bg-[#87997B]  flex">
                            <span class=" m-auto text-[#F4F0BB] font-inter text-xl font-semibold">5 Watt</span>
                        </div>
                         <div class=" w-[6.20981rem] h-[3.9375rem] rounded-lg shadow-power bg-[#87997B] flex">
                            <span class=" m-auto text-[#F4F0BB] font-inter text-xl font-semibold">5 Watt</span>
                        </div>
                         <div class=" w-[6.20981rem] h-[3.9375rem] rounded-lg shadow-power bg-[#87997B] flex">
                            <span class=" m-auto text-[#F4F0BB] font-inter text-xl font-semibold">5 Watt</span>
                        </div>
                    </div>
                    <div class=" absolute w-full  h-4 bg-[#d9d9d94d] blur-sm z-10">

                    </div>
                    <div class=" bg-[#67321D] left-14 w-[1.25rem] h-[96rem] absolute"></div>
                  </div>
                </div>
            </div>

            <div class=" w-full max-w-[400px] flex flex-col items-center space-y-8">
                <div class=" flex items-start h-[2.75rem]">
                     <button class=" rounded-l-lg bg-[#87C38F] hover:bg-[#87C38F] duration-200 hover:text-[#F4F0BB]  w-[8rem] h-full text-[#F4F0BB] font-inter text-xl font-medium">Live</button>
                     <button class=" rounded-r-lg bg-[#F4F0BB] hover:bg-[#87C38F] duration-200 hover:text-[#F4F0BB] w-[8rem] h-full text-[#43291F] font-inter text-xl font-medium">Live</button>
                </div>

                <div class=" w-full rounded-[0.75rem] bg-[#43291F] bg-opacity-40 h-[13.75rem] flex">
                    <span class=" m-auto text-[#F4F0BB] font-inter text-[2rem] font-bold">Data</span>
                </div>
            </div>
         </div>
       </div>
       </div>
    </div>
</template>


<style scoped>


 .card {
    border-radius: 0.75rem;
    background: rgba(217, 217, 217, 0.30);
    box-shadow: 0px 4px 56.8px 14px rgba(0, 0, 0, 0.25);
    backdrop-filter: blur(5.599999904632568px);
 }

 .shadow-power {
    box-shadow: 0px 4px 11.1px 2px rgba(0, 0, 0, 0.40);
 }
</style>