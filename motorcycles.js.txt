/*
  REVIVAL MOTO CO — SINGLE SOURCE OF TRUTH FOR MOTORCYCLE LISTINGS

  Add each motorcycle once in RMC_MOTORCYCLES. The homepage stock cards,
  sold archive and individual motorcycle page all read from this same record,
  helping keep price, mileage, model and derivative consistent.

  Status values: "available", "coming-soon", "reserved", "sold".
  mileageStatus values: "verified", "estimated".

  Copy the object shape below when adding a real bike. Do not publish an
  incomplete record. This example is only a developer comment and never
  appears on the website.

  {
    id: "1995-honda-cbr900rr-fireblade",
    status: "available",
    price: 3995,
    year: 1995,
    make: "Honda",
    model: "CBR900RR FireBlade",
    derivative: "",
    registration: "ABC 123D",
    mileage: 49000,
    mileageStatus: "verified",
    previousOwners: 3,
    colour: "",
    engineCapacity: "893cc",
    shortDescription: "",
    history: "",
    provenance: "",
    originalEquipment: "",
    modifications: "",
    inspectionFindings: "",
    recommissioning: "",
    tyres: "",
    brakes: "",
    consumables: "",
    cosmeticImperfections: "",
    roadTest: "",
    mot: "",
    warranty: "",
    acquisitionStory: "",
    conclusion: "",
    review: "",
    reviewPermission: false,
    images: ["images/example-1.jpg"],
    videoUrl: ""
  }
*/

window.RMC_MOTORCYCLES = [];
