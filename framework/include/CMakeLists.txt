#-----------------------------------------------------------------------------
# Public header files
#-----------------------------------------------------------------------------

set(_public_headers
  cppmicroservices/Any.h
  cppmicroservices/AnyMap.h
  cppmicroservices/Framework.h
  cppmicroservices/FrameworkEvent.h
  cppmicroservices/FrameworkFactory.h
  cppmicroservices/LDAPFilter.h
  cppmicroservices/LDAPProp.h
  cppmicroservices/ListenerToken.h
  cppmicroservices/ListenerFunctors.h
  cppmicroservices/SecurityException.h
  cppmicroservices/SharedLibrary.h
  cppmicroservices/SharedLibraryException.h
  cppmicroservices/ShrinkableMap.h
  cppmicroservices/ShrinkableVector.h
  cppmicroservices/detail/Log.h
  cppmicroservices/detail/Threads.h
  cppmicroservices/detail/WaitCondition.h

  cppmicroservices/PrototypeServiceFactory.h
  cppmicroservices/ServiceEvent.h
  cppmicroservices/ServiceEventListenerHook.h
  cppmicroservices/ServiceException.h
  cppmicroservices/ServiceFactory.h
  cppmicroservices/ServiceFindHook.h
  cppmicroservices/ServiceInterface.h
  cppmicroservices/ServiceListenerHook.h
  cppmicroservices/ServiceObjects.h
  cppmicroservices/ServiceProperties.h
  cppmicroservices/ServiceReference.h
  cppmicroservices/ServiceReferenceBase.h
  cppmicroservices/ServiceRegistration.h
  cppmicroservices/ServiceRegistrationBase.h
  cppmicroservices/ServiceTracker.h
  cppmicroservices/ServiceTrackerCustomizer.h
  cppmicroservices/detail/ServiceTracker.tpp
  cppmicroservices/detail/ServiceTrackerPrivate.h
  cppmicroservices/detail/ServiceTrackerPrivate.tpp
  cppmicroservices/detail/TrackedService.h
  cppmicroservices/detail/TrackedService.tpp
  cppmicroservices/detail/TrackedServiceListener.h

  cppmicroservices/Bundle.h
  cppmicroservices/BundleActivator.h
  cppmicroservices/BundleContext.h
  cppmicroservices/BundleEvent.h
  cppmicroservices/BundleEventHook.h
  cppmicroservices/BundleFindHook.h
  cppmicroservices/BundleImport.h
  cppmicroservices/BundleInitialization.h
  cppmicroservices/BundleResource.h
  cppmicroservices/BundleResourceStream.h
  cppmicroservices/BundleVersion.h
  cppmicroservices/Constants.h
  cppmicroservices/GetBundleContext.h
  cppmicroservices/detail/BundleAbstractTracked.h
  cppmicroservices/detail/BundleAbstractTracked.tpp
  cppmicroservices/detail/BundleResourceBuffer.h
  cppmicroservices/detail/ScopeGuard.h
  cppmicroservices/detail/CounterLatch.h
)
