<script>
    import Icon from '@iconify/svelte'

    import Bar from '../../components/bar.svelte'
</script>

<main class='h-full shadow-2xl p-4'>

    <div class='certifications flex px-12 justify-around items-start mt-12  h-3/4'>

        <section class='flex flex-col gap-4 p-6 bg-slate-200 shadow-2xl'>

            <h1 class='text-2xl text-center'>Professional</h1>

            <div class='flex gap-4 items-center'>
                <Icon icon="ph:x-circle-bold" width={32} color="red" />
                <Icon icon="logos:aws" width={64}/> 
                <div>
                    <p> Certificed Cloud Developer </p>
                    <div class="w-full bg-gray-400 h-1">
                        <div class="bg-blue-600 h-1" style="width: 15%"></div>
                    </div>
                </div>
                
            </div>
            <div class='flex gap-4'>
                <Icon icon="ph:x-circle-bold" width={32} color="red" />
                <Icon icon="logos:aws" width={64}/>
                <div>
                    <p> Certificed Solution Architect </p>
                    <div class="w-full bg-gray-400 h-1">
                        <div class="bg-blue-600 h-1" style="width: 15%"></div>
                    </div>
                </div>
                
            </div>
    
    
    
        </section>
        <section class='flex flex-col p-6 bg-slate-200 shadow-2xl'>
    
            <h1 class='text-2xl text-center'>FreeCodeCamp</h1>
            <div class='flex gap-4 items-center'>
                <Icon icon="ph:x-circle-bold" width={32} color="red" />
                <Icon icon="fluent:phone-laptop-16-regular" color="gray" width={64} />
                <div class=''>
                    <p> Responsive Web Design </p>
                    <div class="w-full bg-gray-400 h-1">
                        <div class="bg-blue-600 h-1" style="width: 25%"></div>
                    </div>
                </div>
                
            </div>
            <div class='flex gap-4 items-center'>
                <Icon icon="ph:x-circle-bold" width={32} color="red" />
                <Icon icon="logos:javascript" color="gray" width={64}/>
                <div>
                    <p> Data Structures and Algorithms </p>
                    <div class="w-full bg-gray-400 h-1">
                        <div class="bg-blue-600 h-1" style="width: 25%"></div>
                    </div>
                </div>
                
            </div>
            <div class='flex gap-4 items-center'>
                <Icon icon="ph:x-circle-bold" width={32} color="red" />
                <Icon icon="material-symbols:database" color="blue" width={64}/>
                <div>
                    <p> Relational Database </p>
                    <div class="w-full bg-gray-400 h-1">
                        <div class="bg-blue-600 h-1" style="width: 1%"></div>
                    </div>
                </div>
                
            </div>
        </section>

    </div>
    <section class='about-certs flex flex-col items-center mb-12 justify-center'>
        <h1>Resources I use:</h1>
        <div class='flex gap-4 justify-center items-center'>
            <Icon icon="logos:udemy" color="gray" width={64}/>
            <Icon icon="simple-icons:freecodecamp" color="green" width={48}/>

        </div>
        
    </section>


</main>

