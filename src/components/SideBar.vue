<template>
    <div class="navBar">
        <router-link  to="/adversarycombiner" class="navElement">
            <div class="svgWrap">
            <svg width="32px" height="36px" viewBox="0 0 160.635 183.044">
			<path fill="none" stroke="currentColor" stroke-width="10" stroke-miterlimit="10" d="M106.661,36.165
				c-0.097-5.499,0.137-9.999,0.519-9.999s5.822,0.776,11.24,1.725l30.279,5.334c5.42,0.933,5.522,2.913,0.228,4.399l-25.391,7.563
				c-5.302,1.462-9.64,6.287-9.64,10.72s1.855,16.121,4.123,16.121c2.268,0,8.849,3.439,8.849,7.644s4.346,15.318,9.659,15.357
				c5.312,0.039,19.109,4.847,19.109,10.347v62.551c0,5.5-4.5,10.052-10,10.117H77.663c-5.5-0.064-10-4.617-10-10.117v-62.134
				c0-5.5,3.97-10.033,8.822-10.073s17.32-4.034,17.167-8.543c-0.153-4.51,2.362-15.148,4.4-15.148s8.036-4.5,8.061-10L106.661,36.165
				z"/>
			<path fill="none" stroke="currentColor" stroke-width="10" stroke-miterlimit="10" d="M43.998,14.999C43.901,9.5,44.134,5,44.517,5
				s5.822,0.776,11.24,1.725l30.279,5.334c5.42,0.933,5.522,2.913,0.228,4.399l-25.391,7.563c-5.302,1.462-9.64,6.287-9.64,10.72
				s1.855,16.121,4.124,16.121c2.268,0,8.849,3.439,8.849,7.644s4.346,15.318,9.658,15.357c5.313,0.039,19.109,4.847,19.109,10.347
				v62.551c0,5.5-4.5,10.052-10,10.117H15c-5.5-0.064-10-4.617-10-10.117V84.626c0-5.5,3.97-10.033,8.822-10.072
				c4.852-0.04,17.319-4.034,17.167-8.544c-0.153-4.509,2.362-15.148,4.401-15.148s8.035-4.5,8.061-10L43.998,14.999z"/>
            </svg>
            </div>
            <div class="navItemName">
                Adversary Combiner
            </div>
        </router-link>
        <router-link  to="/randomizer" class="navElement">
           <div class="svgWrap"><svg width="36px" height="30px" viewBox="0 0 236.395 198.805">
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="81.238" cy="79.685" r="11.491"/>
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="70.941" cy="121.834" r="11.49"/>
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="41.917" cy="70.593" r="11.49"/>
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="93.758" cy="40.403" r="11.49"/>
           <path fill="none" stroke="currentColor" stroke-width="10" stroke-miterlimit="10" d="M224.677,80.998c5.187,1.83,7.965,7.582,6.174,12.782l-32.1,93.201c-1.791,5.2-7.529,8.044-12.752,6.319l-90.428-31.146c-5.177-1.857-7.947-7.631-6.156-12.832l31.906-92.635c1.791-5.2,7.525-8.031,12.742-6.29L224.677,80.998z"/>
           <path fill="none" stroke="currentColor" stroke-width="10" stroke-miterlimit="10" d="M121.32,56.688c1.791-5.2,3.709-9.347,4.263-9.214c0.553,0.133,0.39-3.213-2.321-7.999l-16.64-29.377c-2.711-4.786-8.861-6.513-13.667-3.838L10.022,53.898c-4.759,2.757-6.436,8.928-3.725,13.713l48.287,85.249c2.711,4.786,8.893,6.571,13.737,3.967l14.018-7.612c4.822-2.645,10.233-9.064,12.024-14.264L121.32,56.688z"/>
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="126.653" cy="140.806" r="11.491"/>
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="197.922" cy="102.864" r="11.491"/>
           <circle fill-rule="evenodd" clip-rule="evenodd" fill="currentColor" cx="161.569" cy="121.834" r="11.491"/>
           </svg></div>
           <div class="navItemName">
                Randomizer
            </div>
        </router-link>
    </div>
</template>

<script>
    export default {
        name: 'CharacterViewer'
    }
</script>

<style scoped>
	.navBar{
		width:220px;
		height: 100%;
		background-color: #040C28;
		border-right: 1px solid rgb(72 108 212 / 50%);
		display:flex;
		flex-direction: column;
		position: fixed;
        top: 0px;
        bottom: 0px;
        left: 0px;
	}
	.navElement { 
		color:#91a2de;
		height:52px;
		width:100%;
		display:flex;
		align-items: center;
		cursor: pointer;
		text-decoration: none;
	}
	.navElement:hover{
		background-color: #091b5b;
		border-right:2px solid #78B6E4;
	}

	.navItemName {
		font-size: 14px;
		padding-right:20px;
		padding-left:16px;
		font-family: Roboto, sans-serif;
		user-select: none;
	}

	.navElement:hover{
		color: #78B6E4;
	}
	.svgWrap{
		padding-left: 20px;
	}
</style>