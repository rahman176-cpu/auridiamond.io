import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

export default function AuridiamondLanding() { return ( <div className="min-h-screen bg-gradient-to-br from-black via-gray-900 to-gray-800 text-white p-6"> <div className="max-w-5xl mx-auto space-y-10"> <header className="text-center space-y-4"> <h1 className="text-5xl font-bold text-yellow-400">Auridiamond ($ARD)</h1> <p className="text-xl text-gray-300 italic"> Where rarity meets brilliance. </p> <p className="text-md text-gray-400 max-w-2xl mx-auto"> Auridiamond is a cryptocurrency that blends the beauty of gold with the clarity of diamonds, representing stability and luxury in a single digital form. Designed for collectors, investors, and lovers of digital luxury. </p> </header>

<section className="grid md:grid-cols-2 gap-6">
      <Card>
        <CardContent className="p-6 space-y-4">
          <h2 className="text-2xl font-semibold text-yellow-300">Why Auridiamond?</h2>
          <ul className="list-disc list-inside space-y-2 text-gray-300">
            <li>Fixed max supply of 100 million units</li>
            <li>No additional minting — designed to preserve value</li>
            <li>Combats inflation via a better digital economic model</li>
            <li>Long-term investment focus, not just speculation</li>
          </ul>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-6 space-y-4">
          <h2 className="text-2xl font-semibold text-yellow-300">Built for Utility</h2>
          <ul className="list-disc list-inside space-y-2 text-gray-300">
            <li>Access to decentralized investment tools</li>
            <li>Protection against fiat inflation</li>
            <li>Real-world value-driven ecosystem</li>
          </ul>
        </CardContent>
      </Card>
    </section>

    <Card>
      <CardContent className="p-6 space-y-4">
        <h2 className="text-2xl font-semibold text-yellow-300">Problems We Solve</h2>
        <p className="text-gray-300">
          Traditional fiat systems suffer from inflation due to constant money printing.
          Auridiamond combats this with:
        </p>
        <ul className="list-disc list-inside space-y-2 text-gray-300">
          <li>Fixed supply — no arbitrary minting</li>
          <li>Demand-driven pricing via bonding curve</li>
        </ul>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-6 space-y-4">
        <h2 className="text-2xl font-semibold text-yellow-300">Powered by Solana</h2>
        <ul className="list-disc list-inside space-y-2 text-gray-300">
          <li>High-speed transactions</li>
          <li>Near-zero fees</li>
          <li>Ideal for mass adoption</li>
          <li>Supports staking, farming, and utility access</li>
        </ul>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-6 space-y-4">
        <h2 className="text-2xl font-semibold text-yellow-300">Anti-Dump Design</h2>
        <p className="text-gray-300">
          Strategic tokenomics built for sustainability:
        </p>
        <ul className="list-disc list-inside space-y-2 text-gray-300">
          <li>55% Bonding Curve — price increases with demand</li>
          <li>35% Vesting — gradual unlock to avoid dumping</li>
          <li>10% Adaptive Liquidity — managed pools for stability</li>
        </ul>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-6 space-y-4">
        <h2 className="text-2xl font-semibold text-yellow-300">Vesting Schedule</h2>
        <ul className="list-disc list-inside space-y-2 text-gray-300">
          <li>3-month cliff period</li>
          <li>Monthly unlocks over 21 months</li>
          <li>24-month total vesting duration</li>
          <li>Mitigates early sell-off risks</li>
        </ul>
      </CardContent>
    </Card>

    <footer className="text-center mt-10 text-gray-500">
      &copy; {new Date().getFullYear()} Auridiamond. Built on Solana.
    </footer>
  </div>
</div>

); }
