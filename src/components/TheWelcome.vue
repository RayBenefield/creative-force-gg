<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
    <WelcomeItem>
        <template #icon>
            <DocumentationIcon />
        </template>
        <template #heading>Problem</template>

        Traditional game development has an ROI problem. It’s <b>high cost</b>,
        <b>high risk</b>, with <b>slow time to market</b>.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <EcosystemIcon />
        </template>
        <template #heading>Solution</template>

        <b>Tableau </b>is our framework to <b>lower investment </b>through rapid
        development and <b>increase returns </b>with responsiveness to market
        conditions.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <ToolingIcon />
        </template>
        <template #heading>Pitch</template>

        We can create a new game <b>every 2 weeks </b>using
        <b>Unreal Editor for Fortnite</b>.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <CommunityIcon />
        </template>
        <template #heading>What is Tableau?</template>

        Platform agnostic framework written in Verse developed using modern day
        enterprise software methodologies to reduce development investment and
        time to market allowing rapid creation of new game genres. It opens the
        opportunity to obtain dominant market share when mixed with the mostly
        untrodden UEFN toolset, the opportunity in the Fortnite ecosystem, and
        the expertise and credentials of the founders in software/game
        development and user research. The software development practices
        followed allow for rapid and stable iteration to mold each game into
        exactly what works in the market, while preparing for the future of
        Unreal Engine 6 with Verse.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <SupportIcon />
        </template>
        <template #heading>Socials</template>
        <b>X/Twitter: </b>
        <br />
        <ul>
            <li>
                <a
                    href="https://x.com/RayBenefield"
                    target="_blank"
                    rel="noopener"
                    >@RayBenefield</a
                >
            </li>
            <li>
                <a
                    href="https://x.com/TerrieMonroe"
                    target="_blank"
                    rel="noopener"
                    >@TerrieMonroe</a
                >
            </li>
        </ul>
        <b>Twitch: </b>
        <br />
        <ul>
            <li>
                <a
                    href="https://twitch.tv/RayBenefield"
                    target="_blank"
                    rel="noopener"
                    >@RayBenefield</a
                >
            </li>
        </ul>
    </WelcomeItem>
</template>
