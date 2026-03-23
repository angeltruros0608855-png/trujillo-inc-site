import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { motion } from "framer-motion";

export default function CarDetailingSite() {
  return (
    <div className="bg-black text-white min-h-screen font-sans">
      {/* HERO */}
      <section className="h-screen flex flex-col justify-center items-center text-center px-6">
        <motion.h1
          initial={{ opacity: 0, y: -20 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.8 }}
          className="text-5xl md:text-7xl font-bold text-red-600"
        >
          TRUJILLO INC.
        </motion.h1>
        <p className="mt-6 text-lg md:text-xl max-w-2xl text-gray-300">
          Power. Precision. Perfection. We don’t just clean cars — we make them untouchable.
        </p>
        <p className="mt-4 text-gray-400">Call Now: 214-482-9152</p>
        <Button className="mt-8 bg-red-600 hover:bg-red-700 text-white text-lg px-8 py-6 rounded-2xl shadow-xl">
          Book Now
        </Button>
      </section>

      {/* SERVICES */}
      <section className="py-20 px-6 bg-white text-black">
        <h2 className="text-4xl font-bold text-center mb-12">
          Our Services
        </h2>
        <div className="grid md:grid-cols-3 gap-8">
          {[
            {
              title: "Interior Detail",
              desc: "Deep cleaning, shampoo, stain removal, and full interior restoration.",
            },
            {
              title: "Exterior Detail",
              desc: "Hand wash, wax, polish, and paint shine enhancement.",
            },
            {
              title: "Full Detail",
              desc: "Complete inside & out transformation. Showroom finish.",
            },
          ].map((service, i) => (
            <Card key={i} className="rounded-2xl shadow-lg">
              <CardContent className="p-6">
                <h3 className="text-2xl font-bold text-red-600 mb-4">
                  {service.title}
                </h3>
                <p className="text-gray-700">{service.desc}</p>
              </CardContent>
            </Card>
          ))}
        </div>
      </section>

      {/* PRICING */}
      <section className="py-20 px-6 bg-black text-white text-center">
        <h2 className="text-4xl font-bold text-red-600 mb-10">Pricing</h2>
        <div className="flex flex-col md:flex-row justify-center gap-8">
          {["Basic Detail - $40","Standard Detail - $70","Full Detail - $100"].map((price, i) => (
            <div key={i} className="border border-red-600 rounded-2xl p-8 w-64 mx-auto">
              <p className="text-xl font-bold">{price}</p>
            </div>
          ))}
        </div>
      </section>

      {/* ABOUT */}
      <section className="py-20 px-6 bg-white text-black text-center">
        <h2 className="text-4xl font-bold text-red-600 mb-6">
          Built Different
        </h2>
        <p className="max-w-3xl mx-auto text-gray-700 text-lg">
          TRUJILLO INC. runs on discipline and results. Every car gets treated like a luxury machine. No shortcuts. No excuses. Just flawless work.
        </p>
      </section>

      {/* CTA */}
      <section className="py-20 px-6 bg-red-600 text-center">
        <h2 className="text-4xl font-bold mb-6">
          Ready to Ride Clean?
        </h2>
        <p className="mb-6 text-lg">Call 214-482-9152 to book now</p>
        <Button className="bg-black hover:bg-gray-900 text-white text-lg px-10 py-6 rounded-2xl shadow-2xl">
          Schedule Your Detail
        </Button>
      </section>

      {/* FOOTER */}
      <footer className="py-8 text-center text-gray-500 bg-black">
        © {new Date().getFullYear()} TRUJILLO INC. All rights reserved.
      </footer>
    </div>
  );
}
