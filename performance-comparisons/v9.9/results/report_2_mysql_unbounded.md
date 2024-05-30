### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 1.7s | 1.698s | 106618.31
| ChannelStore.GetMembers | avg | 3ms | 112ms | 109ms | 3614.21
| RetentionPolicyStore.GetCount | avg | 0s | 3ms | 3ms | 984.50
| EmojiStore.GetMultipleByName | avg | 5ms | 45ms | 40ms | 751.55
| RoleStore.ChannelHigherScopedPermissions | avg | 21ms | 127ms | 106ms | 515.33
| UserStore.AnalyticsGetInactiveUsersCount | avg | 1ms | 6ms | 5ms | 420.98
| RetentionPolicyStore.GetAll | avg | 1ms | 4ms | 3ms | 372.38
| CommandWebhookStore.Cleanup | avg | 2ms | 7ms | 5ms | 300.95
| ChannelStore.GetByNameIncludeDeleted | avg | 49ms | 193ms | 144ms | 293.04
| ChannelStore.AnalyticsTypeCount | avg | 7ms | 18ms | 11ms | 155.75
| ChannelStore.GetSidebarCategory | avg | 40ms | 100ms | 60ms | 148.42
| FileInfoStore.Search | avg | 136ms | 284ms | 148ms | 108.96
| PostPersistentNotificationStore.Get | avg | 3ms | 5ms | 2ms | 78.54
| PostStore.GetPostReminders | avg | 7ms | 12ms | 5ms | 75.31
| UserStore.AnalyticsActiveCount | avg | 239ms | 397ms | 158ms | 66.24
| UserStore.GetMany | avg | 23ms | 38ms | 15ms | 64.86
| ChannelStore.CreateSidebarCategory | avg | 27ms | 41ms | 14ms | 52.71
| JobStore.UpdateStatus | avg | 4ms | 6ms | 2ms | 49.00
| UserAccessTokenStore.GetByToken | avg | 8ms | 12ms | 4ms | 47.09
| TeamStore.AnalyticsTeamCount | avg | 8ms | 11ms | 3ms | 36.05
| StatusStore.UpdateExpiredDNDStatuses | avg | 8ms | 11ms | 3ms | 35.33
| ChannelStore.UpdateSidebarCategories | avg | 118ms | 148ms | 30ms | 25.36
| PostPriorityStore.GetForPost | avg | 39ms | 48ms | 9ms | 23.26
| UserStore.GetByUsername | avg | 42ms | 48ms | 6ms | 14.16
| UserStore.Count | avg | 219ms | 225ms | 6ms | 2.74
| TeamStore.SaveMember | avg | 152ms | 154ms | 2ms | 1.32
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 4.95s | 4.945s | 99873.64
| ChannelStore.GetMembers | p99 | 5ms | 482ms | 477ms | 9636.36
| EmojiStore.GetMultipleByName | p99 | 24ms | 486ms | 462ms | 1893.45
| JobStore.UpdateStatus | p99 | 22ms | 148ms | 126ms | 572.73
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 244ms | 194ms | 391.92
| CommandWebhookStore.Cleanup | p99 | 5ms | 24ms | 19ms | 383.68
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 24ms | 19ms | 383.58
| PostStore.GetPostReminders | p99 | 22ms | 94ms | 72ms | 334.11
| UserStore.AnalyticsActiveCount | p99 | 249ms | 983ms | 734ms | 295.25
| UserStore.Count | p99 | 493ms | 1.915s | 1.422s | 288.24
| ChannelStore.GetByNameIncludeDeleted | p99 | 99ms | 249ms | 150ms | 151.13
| RoleStore.ChannelHigherScopedPermissions | p99 | 421ms | 949ms | 528ms | 125.34
| ChannelStore.GetSidebarCategory | p99 | 415ms | 875ms | 460ms | 110.85
| FileInfoStore.Search | p99 | 249ms | 498ms | 249ms | 100.20
| ChannelStore.AnalyticsTypeCount | p99 | 25ms | 49ms | 24ms | 97.45
| StatusStore.UpdateExpiredDNDStatuses | p99 | 44ms | 87ms | 43ms | 97.18
| PostPersistentNotificationStore.Get | p99 | 41ms | 80ms | 39ms | 95.71
| BotStore.Get | p99 | 484ms | 860ms | 376ms | 77.63
| TeamStore.GetMember | p99 | 53ms | 79ms | 26ms | 49.22
| PostStore.Update | p99 | 97ms | 142ms | 45ms | 46.44
| UserAccessTokenStore.GetByToken | p99 | 205ms | 265ms | 60ms | 29.27
| UserStore.IsEmpty | p99 | 250ms | 306ms | 56ms | 22.44
| PostPriorityStore.GetForPost | p99 | 459ms | 562ms | 103ms | 22.42
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 526ms | 620ms | 94ms | 17.86
| ComplianceStore.MessageExport | p99 | 491ms | 560ms | 69ms | 14.06
| ChannelStore.UpdateSidebarCategories | p99 | 820ms | 932ms | 112ms | 13.66
| ChannelStore.CreateDirectChannel | p99 | 1.87s | 2.085s | 215ms | 11.50
| PostPersistentNotificationStore.DeleteExpired | p99 | 41ms | 45ms | 4ms | 9.82
| JobStore.GetAllByStatus | p99 | 479ms | 521ms | 42ms | 8.76
| ChannelStore.Save | p99 | 680ms | 738ms | 58ms | 8.53
| UserStore.UpdateLastLogin | p99 | 38ms | 41ms | 3ms | 7.97
| FileInfoStore.GetForPost | p99 | 583ms | 629ms | 46ms | 7.89
| UserStore.GetMany | p99 | 224ms | 241ms | 17ms | 7.57
| TeamStore.SaveMember | p99 | 695ms | 743ms | 48ms | 6.91
| ThreadStore.Get | p99 | 462ms | 492ms | 30ms | 6.49
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 535ms | 563ms | 28ms | 5.23
| UserStore.GetAllProfiles | p99 | 428ms | 443ms | 15ms | 3.50
| ChannelStore.GetChannelsByUser | p99 | 417ms | 431ms | 14ms | 3.36
| UserStore.AutocompleteUsersInChannel | p99 | 2.012s | 2.066s | 54ms | 2.68
| UserStore.GetForLogin | p99 | 430ms | 436ms | 6ms | 1.40
| ChannelStore.GetAllChannelMembersForUser | p99 | 397ms | 401ms | 4ms | 1.01
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | avg | 5ms | 0s | -5ms | -110.55
| ChannelStore.GetMemberCountsByGroup | avg | 4ms | 0s | -4ms | -101.06
| DraftStore.Get | avg | 11ms | 0s | -11ms | -100.53
| BotStore.Save | avg | 4ms | 0s | -4ms | -95.01
| ProductNoticesStore.GetViews | avg | 16ms | 1ms | -15ms | -91.14
| PluginStore.Get | avg | 34ms | 3ms | -31ms | -90.22
| UserStore.GetProfilesInChannel | avg | 97ms | 10ms | -87ms | -89.41
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 10ms | 1ms | -9ms | -85.90
| JobStore.GetAllByTypePage | avg | 97ms | 26ms | -71ms | -73.04
| LicenseStore.GetAll | avg | 14ms | 4ms | -10ms | -70.64
| StatusStore.SaveOrUpdate | avg | 34ms | 12ms | -22ms | -64.37
| ChannelStore.GetMembersForUserWithPagination | avg | 45ms | 17ms | -28ms | -61.98
| UserStore.GetProfilesNotInChannel | avg | 83ms | 34ms | -49ms | -58.87
| ChannelStore.GetTeamChannels | avg | 199ms | 91ms | -108ms | -54.40
| SessionStore.GetSessionsExpired | avg | 32ms | 19ms | -13ms | -40.57
| TeamStore.GetTotalMemberCount | avg | 340ms | 227ms | -113ms | -33.20
| StatusStore.GetByIds | avg | 62ms | 43ms | -19ms | -30.71
| UserStore.Update | avg | 13ms | 9ms | -4ms | -29.66
| TeamStore.GetActiveMemberCount | avg | 428ms | 310ms | -118ms | -27.59
| UserStore.Get | avg | 19ms | 14ms | -5ms | -25.66
| PostStore.Delete | avg | 109ms | 81ms | -28ms | -25.61
| PreferenceStore.DeleteCategoryAndName | avg | 8ms | 6ms | -2ms | -24.75
| ThreadStore.GetThreadUnreadReplyCount | avg | 65ms | 52ms | -13ms | -20.12
| JobStore.Get | avg | 81ms | 65ms | -16ms | -19.84
| FileInfoStore.Get | avg | 42ms | 34ms | -8ms | -19.08
| PostStore.GetSingle | avg | 56ms | 46ms | -10ms | -17.83
| ChannelStore.SearchGroupChannels | avg | 68ms | 56ms | -12ms | -17.54
| LinkMetadataStore.Get | avg | 57ms | 47ms | -10ms | -17.52
| UserStore.GetUnreadCount | avg | 46ms | 38ms | -8ms | -17.49
| ChannelStore.GetAllChannelMembersForUser | avg | 36ms | 30ms | -6ms | -16.80
| FileInfoStore.SetContent | avg | 12ms | 10ms | -2ms | -16.56
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 43ms | 36ms | -7ms | -16.19
| PostPriorityStore.GetForPosts | avg | 72ms | 61ms | -11ms | -15.34
| ThreadStore.GetMembershipForUser | avg | 52ms | 44ms | -8ms | -15.25
| ThreadStore.GetThreadForUser | avg | 79ms | 67ms | -12ms | -15.20
| PostStore.GetPostReminderMetadata | avg | 47ms | 40ms | -7ms | -14.90
| EmojiStore.GetByName | avg | 54ms | 46ms | -8ms | -14.86
| TeamStore.Get | avg | 54ms | 46ms | -8ms | -14.83
| PostAcknowledgementStore.GetForPosts | avg | 70ms | 60ms | -10ms | -14.34
| ComplianceStore.MessageExport | avg | 50ms | 43ms | -7ms | -14.03
| ChannelStore.GetMemberForPost | avg | 67ms | 58ms | -9ms | -13.47
| ThreadStore.Get | avg | 67ms | 58ms | -9ms | -13.44
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 582ms | 504ms | -78ms | -13.41
| FileInfoStore.GetForPost | avg | 60ms | 52ms | -8ms | -13.40
| ChannelStore.GetPinnedPostCount | avg | 54ms | 47ms | -7ms | -13.00
| ThreadStore.GetThreadsForUser | avg | 62ms | 54ms | -8ms | -12.97
| UserStore.GetProfileByIds | avg | 32ms | 28ms | -4ms | -12.41
| PreferenceStore.Get | avg | 49ms | 43ms | -6ms | -12.25
| PostStore.GetPostsSince | avg | 75ms | 66ms | -9ms | -11.99
| UserStore.GetProfilesByUsernames | avg | 42ms | 37ms | -5ms | -11.98
| PostStore.Get | avg | 95ms | 84ms | -11ms | -11.56
| JobStore.GetNewestJobByStatusesAndType | avg | 35ms | 31ms | -4ms | -11.50
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 45ms | 40ms | -5ms | -11.07
| PostStore.GetPostsBefore | avg | 54ms | 48ms | -6ms | -11.05
| ThreadStore.GetThreadFollowers | avg | 55ms | 49ms | -6ms | -10.96
| ChannelStore.AutocompleteInTeamForSearch | avg | 315ms | 281ms | -34ms | -10.81
| GroupStore.GetGroups | avg | 56ms | 50ms | -6ms | -10.77
| PostPersistentNotificationStore.GetSingle | avg | 56ms | 50ms | -6ms | -10.64
| PostStore.GetPostsByThread | avg | 56ms | 50ms | -6ms | -10.63
| WebhookStore.GetOutgoingByTeam | avg | 57ms | 51ms | -6ms | -10.46
| ChannelStore.GetMembersForUser | avg | 50ms | 45ms | -5ms | -9.99
| ChannelStore.GetChannels | avg | 51ms | 46ms | -5ms | -9.80
| ChannelStore.GetFileCount | avg | 38ms | 35ms | -3ms | -7.92
| ChannelStore.Save | avg | 67ms | 62ms | -5ms | -7.47
| ReactionStore.GetForPost | avg | 54ms | 50ms | -4ms | -7.40
| GroupStore.GetByName | avg | 31ms | 29ms | -2ms | -6.47
| PostStore.GetEtag | avg | 66ms | 62ms | -4ms | -6.06
| ChannelStore.Get | avg | 94ms | 89ms | -5ms | -5.34
| ThreadStore.GetTotalUnreadMentions | avg | 39ms | 37ms | -2ms | -5.14
| UserStore.Search | avg | 215ms | 204ms | -11ms | -5.13
| PostAcknowledgementStore.GetForPost | avg | 45ms | 43ms | -2ms | -4.40
| ThreadStore.GetTeamsUnreadForUser | avg | 48ms | 46ms | -2ms | -4.19
| ChannelStore.Autocomplete | avg | 2.34s | 2.253s | -87ms | -3.72
| PreferenceStore.GetAll | avg | 59ms | 57ms | -2ms | -3.37
| UserStore.AutocompleteUsersInChannel | avg | 439ms | 426ms | -13ms | -2.96
| ChannelStore.GetMemberCount | avg | 334ms | 328ms | -6ms | -1.80
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Get | p99 | 25ms | 0s | -25ms | -101.21
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| FileInfoStore.DeleteForPost | p99 | 5ms | 0s | -5ms | -100.89
| ChannelStore.GetMemberCountsByGroup | p99 | 49ms | 0s | -49ms | -99.84
| PluginStore.Get | p99 | 465ms | 23ms | -442ms | -95.05
| ChannelStore.GetMembersForUserWithPagination | p99 | 462ms | 48ms | -414ms | -89.52
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 25ms | 5ms | -20ms | -80.45
| ProductNoticesStore.GetViews | p99 | 25ms | 5ms | -20ms | -80.45
| JobStore.Save | p99 | 160ms | 33ms | -127ms | -79.37
| UserStore.GetProfilesInChannel | p99 | 457ms | 95ms | -362ms | -79.13
| JobStore.GetAllByTypePage | p99 | 917ms | 225ms | -692ms | -75.49
| PreferenceStore.DeleteCategoryAndName | p99 | 92ms | 24ms | -68ms | -73.92
| StatusStore.SaveOrUpdate | p99 | 777ms | 216ms | -561ms | -72.17
| ChannelStore.GetTeamChannels | p99 | 975ms | 475ms | -500ms | -51.28
| LicenseStore.GetAll | p99 | 98ms | 48ms | -50ms | -51.21
| TeamStore.GetTotalMemberCount | p99 | 987ms | 492ms | -495ms | -50.13
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 46ms | 24ms | -22ms | -47.83
| UserStore.Update | p99 | 149ms | 83ms | -66ms | -44.16
| FileInfoStore.SetContent | p99 | 134ms | 76ms | -58ms | -43.22
| JobStore.UpdateStatusOptimistically | p99 | 35ms | 22ms | -13ms | -37.41
| PluginStore.List | p99 | 334ms | 217ms | -117ms | -35.01
| ChannelStore.SearchGroupChannels | p99 | 856ms | 566ms | -290ms | -33.89
| JobStore.GetNewestJobByStatusesAndType | p99 | 605ms | 421ms | -184ms | -30.41
| FileInfoStore.AttachToPost | p99 | 71ms | 51ms | -20ms | -28.22
| ThreadStore.GetThreadUnreadReplyCount | p99 | 687ms | 497ms | -190ms | -27.65
| JobStore.GetCountByStatusAndType | p99 | 525ms | 385ms | -140ms | -26.67
| ReactionStore.GetForPost | p99 | 628ms | 492ms | -136ms | -21.66
| ClusterDiscoveryStore.SetLastPingAt | p99 | 60ms | 47ms | -13ms | -21.54
| ThreadStore.GetTeamsUnreadForUser | p99 | 670ms | 534ms | -136ms | -20.31
| LinkMetadataStore.Get | p99 | 618ms | 496ms | -122ms | -19.75
| JobStore.Get | p99 | 931ms | 750ms | -181ms | -19.44
| ThreadStore.UpdateMembership | p99 | 61ms | 50ms | -11ms | -17.99
| WebhookStore.GetOutgoingByTeam | p99 | 621ms | 510ms | -111ms | -17.87
| PostStore.GetSingle | p99 | 593ms | 492ms | -101ms | -17.02
| PostStore.GetPostsSince | p99 | 657ms | 547ms | -110ms | -16.75
| GroupStore.GetGroups | p99 | 598ms | 499ms | -99ms | -16.56
| UserStore.Get | p99 | 359ms | 301ms | -58ms | -16.15
| ThreadStore.GetThreadsForUser | p99 | 664ms | 561ms | -103ms | -15.52
| PostPersistentNotificationStore.GetSingle | p99 | 573ms | 488ms | -85ms | -14.84
| ChannelStore.GetMemberForPost | p99 | 741ms | 641ms | -100ms | -13.49
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.206s | 1.915s | -291ms | -13.19
| TeamStore.Get | p99 | 562ms | 492ms | -70ms | -12.45
| PreferenceStore.Save | p99 | 113ms | 99ms | -14ms | -12.37
| PostStore.SearchPostsForUser | p99 | 1.039s | 913ms | -126ms | -12.12
| ThreadStore.GetMembershipForUser | p99 | 549ms | 483ms | -66ms | -12.02
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 1.122s | 991ms | -131ms | -11.68
| SessionStore.UpdateLastActivityAt | p99 | 44ms | 39ms | -5ms | -11.39
| PreferenceStore.GetAll | p99 | 565ms | 509ms | -56ms | -9.91
| ChannelStore.GetGuestCount | p99 | 657ms | 595ms | -62ms | -9.44
| ChannelStore.IncrementMentionCount | p99 | 44ms | 40ms | -4ms | -9.02
| ProductNoticesStore.View | p99 | 294ms | 269ms | -25ms | -8.50
| ThreadStore.MarkAsRead | p99 | 49ms | 45ms | -4ms | -8.18
| ChannelStore.UpdateLastViewedAt | p99 | 87ms | 80ms | -7ms | -8.09
| UserStore.GetUnreadCount | p99 | 498ms | 458ms | -40ms | -8.03
| PostStore.GetEtag | p99 | 657ms | 605ms | -52ms | -7.91
| ThreadStore.GetThreadForUser | p99 | 917ms | 852ms | -65ms | -7.09
| ChannelStore.GetChannels | p99 | 523ms | 486ms | -37ms | -7.07
| FileInfoStore.Save | p99 | 58ms | 54ms | -4ms | -6.84
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 481ms | 449ms | -32ms | -6.66
| PostStore.Save | p99 | 154ms | 144ms | -10ms | -6.49
| PostPriorityStore.GetForPosts | p99 | 941ms | 890ms | -51ms | -5.42
| PostAcknowledgementStore.GetForPosts | p99 | 930ms | 881ms | -49ms | -5.27
| PostStore.GetPostsByThread | p99 | 524ms | 497ms | -27ms | -5.16
| UserStore.GetProfileByIds | p99 | 460ms | 437ms | -23ms | -5.00
| PostStore.GetPostReminderMetadata | p99 | 444ms | 422ms | -22ms | -4.96
| EmojiStore.GetByName | p99 | 506ms | 482ms | -24ms | -4.74
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 42ms | 40ms | -2ms | -4.72
| ChannelStore.Get | p99 | 830ms | 791ms | -39ms | -4.70
| UserStore.UpdateUpdateAt | p99 | 44ms | 42ms | -2ms | -4.53
| ThreadStore.GetThreadFollowers | p99 | 553ms | 528ms | -25ms | -4.52
| PostStore.GetPostsBefore | p99 | 513ms | 490ms | -23ms | -4.48
| UserStore.GetProfilesNotInChannel | p99 | 246ms | 235ms | -11ms | -4.47
| GroupStore.GetByName | p99 | 426ms | 407ms | -19ms | -4.46
| AuditStore.Save | p99 | 46ms | 44ms | -2ms | -4.35
| ChannelStore.GetPinnedPostCount | p99 | 514ms | 492ms | -22ms | -4.28
| PostStore.GetPostIdBeforeTime | p99 | 47ms | 45ms | -2ms | -4.24
| FileInfoStore.Get | p99 | 474ms | 454ms | -20ms | -4.22
| ThreadStore.MaintainMembership | p99 | 95ms | 91ms | -4ms | -4.20
| StatusStore.GetByIds | p99 | 496ms | 476ms | -20ms | -4.03
| PostStore.Get | p99 | 959ms | 922ms | -37ms | -3.86
| TeamStore.GetActiveMemberCount | p99 | 987ms | 950ms | -37ms | -3.75
| PostStore.GetPostsAfter | p99 | 465ms | 448ms | -17ms | -3.66
| StatusStore.Get | p99 | 389ms | 375ms | -14ms | -3.60
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 2.354s | 2.271s | -83ms | -3.53
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 485ms | 470ms | -15ms | -3.09
| ThreadStore.GetTotalUnreadMentions | p99 | 473ms | 459ms | -14ms | -2.96
| SessionStore.GetLRUSessions | p99 | 430ms | 418ms | -12ms | -2.79
| UserStore.GetProfilesByUsernames | p99 | 473ms | 460ms | -13ms | -2.75
| ChannelStore.GetMember | p99 | 75ms | 73ms | -2ms | -2.68
| ChannelStore.GetMembersForUser | p99 | 494ms | 481ms | -13ms | -2.63
| ChannelStore.GetFileCount | p99 | 456ms | 444ms | -12ms | -2.63
| PreferenceStore.Get | p99 | 498ms | 485ms | -13ms | -2.61
| UserStore.GetByUsername | p99 | 469ms | 457ms | -12ms | -2.56
| TeamStore.GetTeamsForUser | p99 | 387ms | 379ms | -8ms | -2.07
| ChannelStore.GetMemberCount | p99 | 1.264s | 1.239s | -25ms | -1.98
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 478ms | 470ms | -8ms | -1.67
| SessionStore.Save | p99 | 423ms | 417ms | -6ms | -1.42
| ChannelStore.SaveMember | p99 | 2.236s | 2.207s | -29ms | -1.30
| SessionStore.GetSessionsExpired | p99 | 238ms | 235ms | -3ms | -1.26
| ChannelStore.GetByName | p99 | 488ms | 482ms | -6ms | -1.23
| UserTermsOfServiceStore.GetByUser | p99 | 474ms | 469ms | -5ms | -1.05
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 4ms | 112ms | 108ms | 2914.48
| getRolesByNames | avg | 1ms | 3ms | 2ms | 172.52
| searchFiles | avg | 242ms | 626ms | 384ms | 158.75
| logout | avg | 144ms | 317ms | 173ms | 119.78
| updateCategoriesForTeamForUser | avg | 243ms | 398ms | 155ms | 63.68
| getAnalytics | avg | 302ms | 413ms | 111ms | 36.78
| deletePost | avg | 327ms | 375ms | 48ms | 14.69
| getFilteredUsersStats | avg | 153ms | 171ms | 18ms | 11.76
| getChannelUnread | avg | 28ms | 30ms | 2ms | 7.07
| getPostsForChannelAroundLastUnread | avg | 189ms | 202ms | 13ms | 6.88
| login | avg | 189ms | 193ms | 4ms | 2.11
| createDirectChannel | avg | 452ms | 461ms | 9ms | 1.99
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 482ms | 477ms | 9636.36
| logout | p99 | 910ms | 4.525s | 3.615s | 397.26
| getRolesByNames | p99 | 5ms | 24ms | 19ms | 383.84
| searchFiles | p99 | 249ms | 995ms | 746ms | 300.20
| getAnalytics | p99 | 495ms | 975ms | 480ms | 96.92
| getFilteredUsersStats | p99 | 248ms | 488ms | 240ms | 96.83
| deletePost | p99 | 2.26s | 4.4s | 2.14s | 94.69
| getPrevTrialLicense | p99 | 25ms | 48ms | 23ms | 93.04
| patchPost | p99 | 4.637s | 7.9s | 3.263s | 70.36
| createDirectChannel | p99 | 2.399s | 3.149s | 750ms | 31.26
| addChannelMember | p99 | 4.814s | 5.883s | 1.069s | 22.21
| updateCategoriesForTeamForUser | p99 | 2.23s | 2.419s | 189ms | 8.48
| getChannelsForUser | p99 | 420ms | 431ms | 11ms | 2.62
| getChannelMember | p99 | 774ms | 787ms | 13ms | 1.68
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteDraft | avg | 11ms | 0s | -11ms | -99.96
| getLicenseSelfServeStatus | avg | 292ms | 0s | -292ms | -99.84
| getSelfHostedProducts | avg | 51ms | 0s | -51ms | -99.32
| channelMemberCountsByGroup | avg | 4ms | 0s | -4ms | -93.30
| setPostReminder | avg | 360ms | 69ms | -291ms | -80.83
| getJobsByType | avg | 100ms | 23ms | -77ms | -76.66
| createChannel | avg | 1.305s | 547ms | -758ms | -58.06
| createCategoryForTeamForUser | avg | 160ms | 111ms | -49ms | -30.71
| getTeamStats | avg | 441ms | 311ms | -130ms | -29.48
| patchPost | avg | 817ms | 583ms | -234ms | -28.64
| getPrevTrialLicense | avg | 7ms | 5ms | -2ms | -28.55
| getChannel | avg | 111ms | 88ms | -23ms | -20.69
| getPostThread | avg | 338ms | 275ms | -63ms | -18.65
| searchGroupChannels | avg | 68ms | 56ms | -12ms | -17.52
| createPost | avg | 1.538s | 1.279s | -259ms | -16.84
| updateReadStateThreadByUser | avg | 464ms | 388ms | -76ms | -16.37
| unfollowThreadByUser | avg | 132ms | 112ms | -20ms | -15.20
| removeUserCustomStatus | avg | 196ms | 167ms | -29ms | -14.83
| followThreadByUser | avg | 194ms | 168ms | -26ms | -13.43
| saveReaction | avg | 175ms | 152ms | -23ms | -13.13
| viewChannel | avg | 111ms | 97ms | -14ms | -12.60
| updatePreferences | avg | 17ms | 15ms | -2ms | -11.96
| getUsersByNames | avg | 42ms | 37ms | -5ms | -11.80
| addChannelMember | avg | 762ms | 674ms | -88ms | -11.55
| getChannelsForTeamForUser | avg | 53ms | 47ms | -6ms | -11.43
| getProfileImage | avg | 89ms | 79ms | -10ms | -11.28
| getFilePreview | avg | 80ms | 71ms | -9ms | -11.27
| autocompleteChannelsForTeamForSearch | avg | 315ms | 281ms | -34ms | -10.80
| getFileThumbnail | avg | 75ms | 67ms | -8ms | -10.60
| getChannelMembersForTeamForUser | avg | 51ms | 46ms | -5ms | -9.86
| getPostsForChannel | avg | 449ms | 407ms | -42ms | -9.35
| getChannelStats | avg | 56ms | 51ms | -5ms | -8.93
| getThreadsForUser | avg | 59ms | 54ms | -5ms | -8.42
| autocompleteUsers | avg | 358ms | 335ms | -23ms | -6.43
| searchUsers | avg | 219ms | 206ms | -13ms | -5.95
| getChannelMember | avg | 57ms | 54ms | -3ms | -5.27
| getPreferences | avg | 61ms | 58ms | -3ms | -4.90
| searchAllChannels | avg | 2.341s | 2.254s | -87ms | -3.72
| uploadFileStream | avg | 380ms | 367ms | -13ms | -3.42
| getUser | avg | 63ms | 61ms | -2ms | -3.18
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteDraft | p99 | 25ms | 0s | -25ms | -101.21
| getSelfHostedProducts | p99 | 100ms | 0s | -100ms | -100.50
| getLicenseSelfServeStatus | p99 | 495ms | 0s | -495ms | -99.97
| channelMemberCountsByGroup | p99 | 49ms | 0s | -49ms | -99.67
| setPostReminder | p99 | 4.45s | 925ms | -3.525s | -79.22
| getJobsByType | p99 | 918ms | 226ms | -692ms | -75.35
| createChannel | p99 | 4.875s | 2.35s | -2.525s | -51.80
| createCategoryForTeamForUser | p99 | 495ms | 248ms | -247ms | -49.90
| createGroupChannel | p99 | 8.487s | 4.888s | -3.599s | -42.40
| searchGroupChannels | p99 | 856ms | 566ms | -290ms | -33.89
| getPostThread | p99 | 3.124s | 2.469s | -655ms | -20.97
| removeUserCustomStatus | p99 | 935ms | 748ms | -187ms | -20.00
| createUser | p99 | 1.214s | 990ms | -224ms | -18.45
| viewChannel | p99 | 1.195s | 986ms | -209ms | -17.49
| getUsersByIds | p99 | 108ms | 90ms | -18ms | -16.63
| getTeamMember | p99 | 146ms | 123ms | -23ms | -15.77
| getChannelsForTeamForUser | p99 | 582ms | 494ms | -88ms | -15.13
| getChannel | p99 | 957ms | 816ms | -141ms | -14.73
| getCategoriesForTeamForUser | p99 | 1.14s | 992ms | -148ms | -12.98
| getPreferences | p99 | 638ms | 559ms | -79ms | -12.38
| getUser | p99 | 786ms | 698ms | -88ms | -11.19
| autocompleteChannelsForTeamForSearch | p99 | 2.206s | 1.968s | -238ms | -10.79
| getThreadsForUser | p99 | 712ms | 641ms | -71ms | -9.97
| updateReadStateThreadByUser | p99 | 4.293s | 3.964s | -329ms | -7.66
| getProfileImage | p99 | 447ms | 415ms | -32ms | -7.16
| updatePreferences | p99 | 190ms | 177ms | -13ms | -6.84
| getPostsForChannel | p99 | 6.991s | 6.535s | -456ms | -6.52
| createPost | p99 | 8.54s | 7.985s | -555ms | -6.50
| saveReaction | p99 | 2.014s | 1.89s | -124ms | -6.16
| getTeamStats | p99 | 992ms | 950ms | -42ms | -4.24
| getFilePreview | p99 | 491ms | 476ms | -15ms | -3.06
| getFileThumbnail | p99 | 496ms | 482ms | -14ms | -2.82
| getUsersByNames | p99 | 476ms | 463ms | -13ms | -2.73
| getTeamMembersForUser | p99 | 422ms | 411ms | -11ms | -2.60
| getChannelMembersForTeamForUser | p99 | 496ms | 485ms | -11ms | -2.22
| unfollowThreadByUser | p99 | 926ms | 906ms | -20ms | -2.16
| getTeamsUnreadForUser | p99 | 881ms | 862ms | -19ms | -2.16
| getUsers | p99 | 483ms | 478ms | -5ms | -1.04
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 44ms | -2ms | -4.352
| BotStore.Get |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 484ms| 860ms | 376ms | 77.626
| BotStore.Save |  Avg| 4ms| 0s | -4ms | -95.009
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 582ms| 504ms | -78ms | -13.407
| |  P99| 2.354s| 2.271s | -83ms | -3.526
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 43ms | -1ms | -2.257
| ChannelStore.AnalyticsTypeCount |  Avg| 7ms| 18ms | 11ms | 155.748
| |  P99| 25ms| 49ms | 24ms | 97.449
| ChannelStore.Autocomplete |  Avg| 2.34s| 2.253s | -87ms | -3.717
| |  P99| 9.467s| 9.475s | 8ms | 0.085
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 315ms| 281ms | -34ms | -10.806
| |  P99| 2.206s| 1.915s | -291ms | -13.193
| ChannelStore.CreateDirectChannel |  Avg| 177ms| 176ms | -1ms | -0.565
| |  P99| 1.87s| 2.085s | 215ms | 11.497
| ChannelStore.CreateInitialSidebarCategories |  Avg| 66ms| 67ms | 1ms | 1.518
| |  P99| 489ms| 490ms | 1ms | 0.205
| ChannelStore.CreateSidebarCategory |  Avg| 27ms| 41ms | 14ms | 52.707
| |  P99| 50ms| 244ms | 194ms | 391.919
| ChannelStore.Get |  Avg| 94ms| 89ms | -5ms | -5.339
| |  P99| 830ms| 791ms | -39ms | -4.698
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 70ms| 69ms | -1ms | -1.430
| |  P99| 526ms| 620ms | 94ms | 17.862
| ChannelStore.GetAllChannelMembersForUser |  Avg| 36ms| 30ms | -6ms | -16.795
| |  P99| 397ms| 401ms | 4ms | 1.009
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 61ms| 60ms | -1ms | -1.637
| |  P99| 535ms| 563ms | 28ms | 5.234
| ChannelStore.GetByName |  Avg| 47ms| 47ms | 0s | 0.000
| |  P99| 488ms| 482ms | -6ms | -1.228
| ChannelStore.GetByNameIncludeDeleted |  Avg| 49ms| 193ms | 144ms | 293.040
| |  P99| 99ms| 249ms | 150ms | 151.134
| ChannelStore.GetChannelUnread |  Avg| 26ms| 27ms | 1ms | 3.870
| |  P99| 374ms| 377ms | 3ms | 0.802
| ChannelStore.GetChannels |  Avg| 51ms| 46ms | -5ms | -9.802
| |  P99| 523ms| 486ms | -37ms | -7.073
| ChannelStore.GetChannelsByUser |  Avg| 33ms| 34ms | 1ms | 2.991
| |  P99| 417ms| 431ms | 14ms | 3.356
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 45ms| 40ms | -5ms | -11.067
| |  P99| 485ms| 470ms | -15ms | -3.092
| ChannelStore.GetFileCount |  Avg| 38ms| 35ms | -3ms | -7.918
| |  P99| 456ms| 444ms | -12ms | -2.629
| ChannelStore.GetGuestCount |  Avg| 66ms| 65ms | -1ms | -1.506
| |  P99| 657ms| 595ms | -62ms | -9.436
| ChannelStore.GetMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 75ms| 73ms | -2ms | -2.680
| ChannelStore.GetMemberCount |  Avg| 334ms| 328ms | -6ms | -1.799
| |  P99| 1.264s| 1.239s | -25ms | -1.978
| ChannelStore.GetMemberCountsByGroup |  Avg| 4ms| 0s | -4ms | -101.058
| |  P99| 49ms| 0s | -49ms | -99.835
| ChannelStore.GetMemberForPost |  Avg| 67ms| 58ms | -9ms | -13.468
| |  P99| 741ms| 641ms | -100ms | -13.491
| ChannelStore.GetMemberLastViewedAt |  Avg| 34ms| 35ms | 1ms | 2.921
| |  P99| 449ms| 453ms | 4ms | 0.890
| ChannelStore.GetMembers |  Avg| 3ms| 112ms | 109ms | 3614.208
| |  P99| 5ms| 482ms | 477ms | 9636.364
| ChannelStore.GetMembersForUser |  Avg| 50ms| 45ms | -5ms | -9.985
| |  P99| 494ms| 481ms | -13ms | -2.633
| ChannelStore.GetMembersForUserWithPagination |  Avg| 45ms| 17ms | -28ms | -61.984
| |  P99| 462ms| 48ms | -414ms | -89.516
| ChannelStore.GetPinnedPostCount |  Avg| 54ms| 47ms | -7ms | -13.005
| |  P99| 514ms| 492ms | -22ms | -4.282
| ChannelStore.GetPublicChannelsForTeam |  Avg| 64ms| 65ms | 1ms | 1.569
| |  P99| 484ms| 483ms | -1ms | -0.207
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 98ms| 98ms | 0s | 0.000
| |  P99| 1.122s| 991ms | -131ms | -11.679
| ChannelStore.GetSidebarCategory |  Avg| 40ms| 100ms | 60ms | 148.417
| |  P99| 415ms| 875ms | 460ms | 110.846
| ChannelStore.GetTeamChannels |  Avg| 199ms| 91ms | -108ms | -54.400
| |  P99| 975ms| 475ms | -500ms | -51.283
| ChannelStore.IncrementMentionCount |  Avg| 4ms| 3ms | -1ms | -27.852
| |  P99| 44ms| 40ms | -4ms | -9.023
| ChannelStore.Save |  Avg| 67ms| 62ms | -5ms | -7.469
| |  P99| 680ms| 738ms | 58ms | 8.530
| ChannelStore.SaveMember |  Avg| 214ms| 216ms | 2ms | 0.934
| |  P99| 2.236s| 2.207s | -29ms | -1.297
| ChannelStore.SearchGroupChannels |  Avg| 68ms| 56ms | -12ms | -17.539
| |  P99| 856ms| 566ms | -290ms | -33.890
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 8ms | -1ms | -11.437
| |  P99| 87ms| 80ms | -7ms | -8.091
| ChannelStore.UpdateSidebarCategories |  Avg| 118ms| 148ms | 30ms | 25.357
| |  P99| 820ms| 932ms | 112ms | 13.658
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 40ms | -2ms | -4.724
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 6ms| 5ms | -1ms | -16.976
| |  P99| 60ms| 47ms | -13ms | -21.545
| CommandWebhookStore.Cleanup |  Avg| 2ms| 7ms | 5ms | 300.953
| |  P99| 5ms| 24ms | 19ms | 383.680
| ComplianceStore.MessageExport |  Avg| 50ms| 43ms | -7ms | -14.027
| |  P99| 491ms| 560ms | 69ms | 14.061
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 24ms | -22ms | -47.828
| DraftStore.Get |  Avg| 11ms| 0s | -11ms | -100.535
| |  P99| 25ms| 0s | -25ms | -101.215
| EmojiStore.GetByName |  Avg| 54ms| 46ms | -8ms | -14.856
| |  P99| 506ms| 482ms | -24ms | -4.741
| EmojiStore.GetMultipleByName |  Avg| 5ms| 45ms | 40ms | 751.550
| |  P99| 24ms| 486ms | 462ms | 1893.452
| FileInfoStore.AttachToPost |  Avg| 8ms| 7ms | -1ms | -13.009
| |  P99| 71ms| 51ms | -20ms | -28.225
| FileInfoStore.DeleteForPost |  Avg| 5ms| 0s | -5ms | -110.552
| |  P99| 5ms| 0s | -5ms | -100.892
| FileInfoStore.Get |  Avg| 42ms| 34ms | -8ms | -19.077
| |  P99| 474ms| 454ms | -20ms | -4.218
| FileInfoStore.GetForPost |  Avg| 60ms| 52ms | -8ms | -13.404
| |  P99| 583ms| 629ms | 46ms | 7.895
| FileInfoStore.Save |  Avg| 7ms| 6ms | -1ms | -15.298
| |  P99| 58ms| 54ms | -4ms | -6.841
| FileInfoStore.Search |  Avg| 136ms| 284ms | 148ms | 108.955
| |  P99| 249ms| 498ms | 249ms | 100.201
| FileInfoStore.SetContent |  Avg| 12ms| 10ms | -2ms | -16.555
| |  P99| 134ms| 76ms | -58ms | -43.221
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 49ms| 49ms | 0s | 0.000
| |  P99| 482ms| 482ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 31ms| 29ms | -2ms | -6.470
| |  P99| 426ms| 407ms | -19ms | -4.461
| GroupStore.GetGroups |  Avg| 56ms| 50ms | -6ms | -10.768
| |  P99| 598ms| 499ms | -99ms | -16.556
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 10ms| 1ms | -9ms | -85.900
| |  P99| 25ms| 5ms | -20ms | -80.451
| JobStore.Get |  Avg| 81ms| 65ms | -16ms | -19.840
| |  P99| 931ms| 750ms | -181ms | -19.441
| JobStore.GetAllByStatus |  Avg| 47ms| 48ms | 1ms | 2.108
| |  P99| 479ms| 521ms | 42ms | 8.763
| JobStore.GetAllByTypePage |  Avg| 97ms| 26ms | -71ms | -73.039
| |  P99| 917ms| 225ms | -692ms | -75.490
| JobStore.GetCountByStatusAndType |  Avg| 30ms| 29ms | -1ms | -3.330
| |  P99| 525ms| 385ms | -140ms | -26.667
| JobStore.GetNewestJobByStatusesAndType |  Avg| 35ms| 31ms | -4ms | -11.503
| |  P99| 605ms| 421ms | -184ms | -30.413
| JobStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 160ms| 33ms | -127ms | -79.375
| JobStore.UpdateOptimistically |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.201
| JobStore.UpdateStatus |  Avg| 4ms| 6ms | 2ms | 49.000
| |  P99| 22ms| 148ms | 126ms | 572.727
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -19.567
| |  P99| 35ms| 22ms | -13ms | -37.411
| LicenseStore.GetAll |  Avg| 14ms| 4ms | -10ms | -70.641
| |  P99| 98ms| 48ms | -50ms | -51.213
| LinkMetadataStore.Get |  Avg| 57ms| 47ms | -10ms | -17.517
| |  P99| 618ms| 496ms | -122ms | -19.751
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.367
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.191
| PluginStore.Get |  Avg| 34ms| 3ms | -31ms | -90.222
| |  P99| 465ms| 23ms | -442ms | -95.054
| PluginStore.List |  Avg| 18ms| 19ms | 1ms | 5.679
| |  P99| 334ms| 217ms | -117ms | -35.012
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.025
| PostAcknowledgementStore.GetForPost |  Avg| 45ms| 43ms | -2ms | -4.402
| |  P99| 723ms| 728ms | 5ms | 0.691
| PostAcknowledgementStore.GetForPosts |  Avg| 70ms| 60ms | -10ms | -14.339
| |  P99| 930ms| 881ms | -49ms | -5.267
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 3ms | 1ms | 40.147
| |  P99| 41ms| 45ms | 4ms | 9.816
| PostPersistentNotificationStore.Get |  Avg| 3ms| 5ms | 2ms | 78.541
| |  P99| 41ms| 80ms | 39ms | 95.706
| PostPersistentNotificationStore.GetSingle |  Avg| 56ms| 50ms | -6ms | -10.637
| |  P99| 573ms| 488ms | -85ms | -14.842
| PostPriorityStore.GetForPost |  Avg| 39ms| 48ms | 9ms | 23.258
| |  P99| 459ms| 562ms | 103ms | 22.423
| PostPriorityStore.GetForPosts |  Avg| 72ms| 61ms | -11ms | -15.343
| |  P99| 941ms| 890ms | -51ms | -5.419
| PostStore.AnalyticsPostCount |  Avg| 2ms| 1.7s | 1.698s | 106618.310
| |  P99| 5ms| 4.95s | 4.945s | 99873.644
| PostStore.Delete |  Avg| 109ms| 81ms | -28ms | -25.612
| |  P99| 480ms| 480ms | 0s | 0.000
| PostStore.Get |  Avg| 95ms| 84ms | -11ms | -11.563
| |  P99| 959ms| 922ms | -37ms | -3.859
| PostStore.GetEtag |  Avg| 66ms| 62ms | -4ms | -6.064
| |  P99| 657ms| 605ms | -52ms | -7.909
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.244
| PostStore.GetPostReminderMetadata |  Avg| 47ms| 40ms | -7ms | -14.899
| |  P99| 444ms| 422ms | -22ms | -4.958
| PostStore.GetPostReminders |  Avg| 7ms| 12ms | 5ms | 75.306
| |  P99| 22ms| 94ms | 72ms | 334.107
| PostStore.GetPosts |  Avg| 35ms| 36ms | 1ms | 2.822
| |  P99| 443ms| 440ms | -3ms | -0.677
| PostStore.GetPostsAfter |  Avg| 41ms| 42ms | 1ms | 2.444
| |  P99| 465ms| 448ms | -17ms | -3.658
| PostStore.GetPostsBefore |  Avg| 54ms| 48ms | -6ms | -11.054
| |  P99| 513ms| 490ms | -23ms | -4.479
| PostStore.GetPostsByThread |  Avg| 56ms| 50ms | -6ms | -10.629
| |  P99| 524ms| 497ms | -27ms | -5.156
| PostStore.GetPostsSince |  Avg| 75ms| 66ms | -9ms | -11.993
| |  P99| 657ms| 547ms | -110ms | -16.748
| PostStore.GetSingle |  Avg| 56ms| 46ms | -10ms | -17.830
| |  P99| 593ms| 492ms | -101ms | -17.022
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 17ms| 16ms | -1ms | -5.951
| |  P99| 154ms| 144ms | -10ms | -6.486
| PostStore.SearchPostsForUser |  Avg| 110ms| 109ms | -1ms | -0.912
| |  P99| 1.039s| 913ms | -126ms | -12.123
| PostStore.SetPostReminder |  Avg| 11ms| 10ms | -1ms | -9.069
| |  P99| 47ms| 46ms | -1ms | -2.116
| PostStore.Update |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 97ms| 142ms | 45ms | 46.441
| PreferenceStore.DeleteCategoryAndName |  Avg| 8ms| 6ms | -2ms | -24.751
| |  P99| 92ms| 24ms | -68ms | -73.916
| PreferenceStore.Get |  Avg| 49ms| 43ms | -6ms | -12.251
| |  P99| 498ms| 485ms | -13ms | -2.610
| PreferenceStore.GetAll |  Avg| 59ms| 57ms | -2ms | -3.365
| |  P99| 565ms| 509ms | -56ms | -9.912
| PreferenceStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 113ms| 99ms | -14ms | -12.373
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 16ms| 1ms | -15ms | -91.139
| |  P99| 25ms| 5ms | -20ms | -80.451
| ProductNoticesStore.View |  Avg| 47ms| 46ms | -1ms | -2.110
| |  P99| 294ms| 269ms | -25ms | -8.500
| ReactionStore.GetForPost |  Avg| 54ms| 50ms | -4ms | -7.403
| |  P99| 628ms| 492ms | -136ms | -21.662
| RetentionPolicyStore.GetAll |  Avg| 1ms| 4ms | 3ms | 372.383
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 0s| 3ms | 3ms | 984.503
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 21ms| 127ms | 106ms | 515.328
| |  P99| 421ms| 949ms | 528ms | 125.341
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 480ms| 480ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 31ms| 30ms | -1ms | -3.215
| |  P99| 430ms| 418ms | -12ms | -2.794
| SessionStore.GetSessionsExpired |  Avg| 32ms| 19ms | -13ms | -40.572
| |  P99| 238ms| 235ms | -3ms | -1.261
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 43ms| 36ms | -7ms | -16.188
| |  P99| 481ms| 449ms | -32ms | -6.658
| SessionStore.Remove |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| SessionStore.Save |  Avg| 34ms| 33ms | -1ms | -2.938
| |  P99| 423ms| 417ms | -6ms | -1.417
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 39ms | -5ms | -11.394
| StatusStore.Get |  Avg| 26ms| 25ms | -1ms | -3.814
| |  P99| 389ms| 375ms | -14ms | -3.603
| StatusStore.GetByIds |  Avg| 62ms| 43ms | -19ms | -30.714
| |  P99| 496ms| 476ms | -20ms | -4.030
| StatusStore.SaveOrUpdate |  Avg| 34ms| 12ms | -22ms | -64.374
| |  P99| 777ms| 216ms | -561ms | -72.167
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 11ms | 3ms | 35.329
| |  P99| 44ms| 87ms | 43ms | 97.175
| StatusStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.118
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.631
| TeamStore.AnalyticsTeamCount |  Avg| 8ms| 11ms | 3ms | 36.046
| |  P99| 49ms| 49ms | 0s | 0.000
| TeamStore.Get |  Avg| 54ms| 46ms | -8ms | -14.828
| |  P99| 562ms| 492ms | -70ms | -12.446
| TeamStore.GetActiveMemberCount |  Avg| 428ms| 310ms | -118ms | -27.591
| |  P99| 987ms| 950ms | -37ms | -3.747
| TeamStore.GetAllPage |  Avg| 43ms| 43ms | 0s | 0.000
| |  P99| 477ms| 476ms | -1ms | -0.210
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 41ms| 42ms | 1ms | 2.420
| |  P99| 469ms| 465ms | -4ms | -0.852
| TeamStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 53ms| 79ms | 26ms | 49.222
| TeamStore.GetTeamsByUserId |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 479ms| 475ms | -4ms | -0.836
| TeamStore.GetTeamsForUser |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 387ms| 379ms | -8ms | -2.066
| TeamStore.GetTotalMemberCount |  Avg| 340ms| 227ms | -113ms | -33.196
| |  P99| 987ms| 492ms | -495ms | -50.127
| TeamStore.SaveMember |  Avg| 152ms| 154ms | 2ms | 1.320
| |  P99| 695ms| 743ms | 48ms | 6.908
| ThreadStore.Get |  Avg| 67ms| 58ms | -9ms | -13.444
| |  P99| 462ms| 492ms | 30ms | 6.492
| ThreadStore.GetMembershipForUser |  Avg| 52ms| 44ms | -8ms | -15.251
| |  P99| 549ms| 483ms | -66ms | -12.021
| ThreadStore.GetTeamsUnreadForUser |  Avg| 48ms| 46ms | -2ms | -4.193
| |  P99| 670ms| 534ms | -136ms | -20.308
| ThreadStore.GetThreadFollowers |  Avg| 55ms| 49ms | -6ms | -10.955
| |  P99| 553ms| 528ms | -25ms | -4.520
| ThreadStore.GetThreadForUser |  Avg| 79ms| 67ms | -12ms | -15.203
| |  P99| 917ms| 852ms | -65ms | -7.086
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 65ms| 52ms | -13ms | -20.122
| |  P99| 687ms| 497ms | -190ms | -27.650
| ThreadStore.GetThreadsForUser |  Avg| 62ms| 54ms | -8ms | -12.967
| |  P99| 664ms| 561ms | -103ms | -15.516
| ThreadStore.GetTotalThreads |  Avg| 38ms| 39ms | 1ms | 2.602
| |  P99| 463ms| 463ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 39ms| 37ms | -2ms | -5.141
| |  P99| 473ms| 459ms | -14ms | -2.962
| ThreadStore.GetTotalUnreadThreads |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 466ms| 464ms | -2ms | -0.429
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 39ms| 38ms | -1ms | -2.564
| |  P99| 478ms| 470ms | -8ms | -1.673
| ThreadStore.MaintainMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 91ms | -4ms | -4.203
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.143
| ThreadStore.MarkAsRead |  Avg| 6ms| 5ms | -1ms | -17.717
| |  P99| 49ms| 45ms | -4ms | -8.181
| ThreadStore.UpdateMembership |  Avg| 6ms| 5ms | -1ms | -17.400
| |  P99| 61ms| 50ms | -11ms | -17.993
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 12ms | 4ms | 47.086
| |  P99| 205ms| 265ms | 60ms | 29.268
| UserStore.AnalyticsActiveCount |  Avg| 239ms| 397ms | 158ms | 66.242
| |  P99| 249ms| 983ms | 734ms | 295.247
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 6ms | 5ms | 420.984
| |  P99| 5ms| 24ms | 19ms | 383.582
| UserStore.AutocompleteUsersInChannel |  Avg| 439ms| 426ms | -13ms | -2.959
| |  P99| 2.012s| 2.066s | 54ms | 2.684
| UserStore.Count |  Avg| 219ms| 225ms | 6ms | 2.744
| |  P99| 493ms| 1.915s | 1.422s | 288.243
| UserStore.Get |  Avg| 19ms| 14ms | -5ms | -25.659
| |  P99| 359ms| 301ms | -58ms | -16.148
| UserStore.GetAllProfiles |  Avg| 35ms| 36ms | 1ms | 2.873
| |  P99| 428ms| 443ms | 15ms | 3.503
| UserStore.GetAllProfilesInChannel |  Avg| 833ms| 830ms | -3ms | -0.360
| |  P99| 2.464s| 2.467s | 3ms | 0.122
| UserStore.GetByUsername |  Avg| 42ms| 48ms | 6ms | 14.156
| |  P99| 469ms| 457ms | -12ms | -2.557
| UserStore.GetForLogin |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 430ms| 436ms | 6ms | 1.396
| UserStore.GetMany |  Avg| 23ms| 38ms | 15ms | 64.858
| |  P99| 224ms| 241ms | 17ms | 7.572
| UserStore.GetProfileByIds |  Avg| 32ms| 28ms | -4ms | -12.412
| |  P99| 460ms| 437ms | -23ms | -4.995
| UserStore.GetProfilesByUsernames |  Avg| 42ms| 37ms | -5ms | -11.976
| |  P99| 473ms| 460ms | -13ms | -2.747
| UserStore.GetProfilesInChannel |  Avg| 97ms| 10ms | -87ms | -89.415
| |  P99| 457ms| 95ms | -362ms | -79.128
| UserStore.GetProfilesNotInChannel |  Avg| 83ms| 34ms | -49ms | -58.873
| |  P99| 246ms| 235ms | -11ms | -4.467
| UserStore.GetUnreadCount |  Avg| 46ms| 38ms | -8ms | -17.490
| |  P99| 498ms| 458ms | -40ms | -8.034
| UserStore.IsEmpty |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 250ms| 306ms | 56ms | 22.436
| UserStore.Save |  Avg| 74ms| 74ms | 0s | 0.000
| |  P99| 234ms| 233ms | -1ms | -0.428
| UserStore.Search |  Avg| 215ms| 204ms | -11ms | -5.128
| |  P99| 968ms| 968ms | 0s | 0.000
| UserStore.Update |  Avg| 13ms| 9ms | -4ms | -29.659
| |  P99| 149ms| 83ms | -66ms | -44.155
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 43ms | -1ms | -2.255
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.967
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.534
| UserTermsOfServiceStore.GetByUser |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 474ms| 469ms | -5ms | -1.054
| WebhookStore.GetOutgoingByTeam |  Avg| 57ms| 51ms | -6ms | -10.458
| |  P99| 621ms| 510ms | -111ms | -17.869
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 762ms| 674ms | -88ms | -11.548
| | P99| 4.814s| 5.883s | 1.069s | 22.208
| addTeamMember | Avg| 2.461s| 2.478s | 17ms | 0.691
| | P99| 9.981s| 9.896s | -85ms | -0.852
| autocompleteChannelsForTeamForSearch | Avg| 315ms| 281ms | -34ms | -10.803
| | P99| 2.206s| 1.968s | -238ms | -10.791
| autocompleteUsers | Avg| 358ms| 335ms | -23ms | -6.433
| | P99| 1.859s| 1.861s | 2ms | 0.108
| channelMemberCountsByGroup | Avg| 4ms| 0s | -4ms | -93.302
| | P99| 49ms| 0s | -49ms | -99.666
| createCategoryForTeamForUser | Avg| 160ms| 111ms | -49ms | -30.705
| | P99| 495ms| 248ms | -247ms | -49.899
| createChannel | Avg| 1.305s| 547ms | -758ms | -58.062
| | P99| 4.875s| 2.35s | -2.525s | -51.796
| createDirectChannel | Avg| 452ms| 461ms | 9ms | 1.991
| | P99| 2.399s| 3.149s | 750ms | 31.264
| createGroupChannel | Avg| 860ms| 855ms | -5ms | -0.582
| | P99| 8.487s| 4.888s | -3.599s | -42.404
| createPost | Avg| 1.538s| 1.279s | -259ms | -16.844
| | P99| 8.54s| 7.985s | -555ms | -6.499
| createUser | Avg| 218ms| 217ms | -1ms | -0.458
| | P99| 1.214s| 990ms | -224ms | -18.446
| deleteDraft | Avg| 11ms| 0s | -11ms | -99.961
| | P99| 25ms| 0s | -25ms | -101.215
| deletePost | Avg| 327ms| 375ms | 48ms | 14.691
| | P99| 2.26s| 4.4s | 2.14s | 94.694
| followThreadByUser | Avg| 194ms| 168ms | -26ms | -13.430
| | P99| 962ms| 964ms | 2ms | 0.208
| getAllTeams | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 489ms| 488ms | -1ms | -0.204
| getAnalytics | Avg| 302ms| 413ms | 111ms | 36.781
| | P99| 495ms| 975ms | 480ms | 96.921
| getCategoriesForTeamForUser | Avg| 99ms| 98ms | -1ms | -1.011
| | P99| 1.14s| 992ms | -148ms | -12.978
| getChannel | Avg| 111ms| 88ms | -23ms | -20.692
| | P99| 957ms| 816ms | -141ms | -14.728
| getChannelMember | Avg| 57ms| 54ms | -3ms | -5.271
| | P99| 774ms| 787ms | 13ms | 1.681
| getChannelMembers | Avg| 4ms| 112ms | 108ms | 2914.477
| | P99| 5ms| 482ms | 477ms | 9636.364
| getChannelMembersForTeamForUser | Avg| 51ms| 46ms | -5ms | -9.855
| | P99| 496ms| 485ms | -11ms | -2.216
| getChannelStats | Avg| 56ms| 51ms | -5ms | -8.934
| | P99| 942ms| 933ms | -9ms | -0.956
| getChannelUnread | Avg| 28ms| 30ms | 2ms | 7.070
| | P99| 408ms| 407ms | -1ms | -0.245
| getChannelsForTeamForUser | Avg| 53ms| 47ms | -6ms | -11.429
| | P99| 582ms| 494ms | -88ms | -15.126
| getChannelsForUser | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 420ms| 431ms | 11ms | 2.617
| getClientConfig | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 231ms| 232ms | 1ms | 0.432
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 80ms| 71ms | -9ms | -11.273
| | P99| 491ms| 476ms | -15ms | -3.056
| getFileThumbnail | Avg| 75ms| 67ms | -8ms | -10.597
| | P99| 496ms| 482ms | -14ms | -2.823
| getFilteredUsersStats | Avg| 153ms| 171ms | 18ms | 11.764
| | P99| 248ms| 488ms | 240ms | 96.833
| getJobsByType | Avg| 100ms| 23ms | -77ms | -76.657
| | P99| 918ms| 226ms | -692ms | -75.353
| getLicenseSelfServeStatus | Avg| 292ms| 0s | -292ms | -99.836
| | P99| 495ms| 0s | -495ms | -99.967
| getPostThread | Avg| 338ms| 275ms | -63ms | -18.653
| | P99| 3.124s| 2.469s | -655ms | -20.969
| getPostsForChannel | Avg| 449ms| 407ms | -42ms | -9.346
| | P99| 6.991s| 6.535s | -456ms | -6.523
| getPostsForChannelAroundLastUnread | Avg| 189ms| 202ms | 13ms | 6.883
| | P99| 2.336s| 2.352s | 16ms | 0.685
| getPreferences | Avg| 61ms| 58ms | -3ms | -4.904
| | P99| 638ms| 559ms | -79ms | -12.381
| getPrevTrialLicense | Avg| 7ms| 5ms | -2ms | -28.553
| | P99| 25ms| 48ms | 23ms | 93.043
| getProfileImage | Avg| 89ms| 79ms | -10ms | -11.280
| | P99| 447ms| 415ms | -32ms | -7.161
| getPublicChannelsForTeam | Avg| 65ms| 66ms | 1ms | 1.528
| | P99| 484ms| 483ms | -1ms | -0.207
| getRolesByNames | Avg| 1ms| 3ms | 2ms | 172.524
| | P99| 5ms| 24ms | 19ms | 383.838
| getSelfHostedProducts | Avg| 51ms| 0s | -51ms | -99.322
| | P99| 100ms| 0s | -100ms | -100.503
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 8ms| 7ms | -1ms | -13.292
| | P99| 146ms| 123ms | -23ms | -15.773
| getTeamMembersForUser | Avg| 30ms| 29ms | -1ms | -3.327
| | P99| 422ms| 411ms | -11ms | -2.605
| getTeamStats | Avg| 441ms| 311ms | -130ms | -29.477
| | P99| 992ms| 950ms | -42ms | -4.235
| getTeamsForUser | Avg| 46ms| 45ms | -1ms | -2.196
| | P99| 479ms| 475ms | -4ms | -0.836
| getTeamsUnreadForUser | Avg| 67ms| 66ms | -1ms | -1.503
| | P99| 881ms| 862ms | -19ms | -2.156
| getThreadsForUser | Avg| 59ms| 54ms | -5ms | -8.416
| | P99| 712ms| 641ms | -71ms | -9.969
| getUser | Avg| 63ms| 61ms | -2ms | -3.183
| | P99| 786ms| 698ms | -88ms | -11.193
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 33ms| 32ms | -1ms | -3.042
| | P99| 483ms| 478ms | -5ms | -1.035
| getUsersByIds | Avg| 5ms| 4ms | -1ms | -22.056
| | P99| 108ms| 90ms | -18ms | -16.633
| getUsersByNames | Avg| 42ms| 37ms | -5ms | -11.798
| | P99| 476ms| 463ms | -13ms | -2.730
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 189ms| 193ms | 4ms | 2.114
| | P99| 1.955s| 1.957s | 2ms | 0.102
| logout | Avg| 144ms| 317ms | 173ms | 119.775
| | P99| 910ms| 4.525s | 3.615s | 397.256
| patchPost | Avg| 817ms| 583ms | -234ms | -28.638
| | P99| 4.637s| 7.9s | 3.263s | 70.364
| removeUserCustomStatus | Avg| 196ms| 167ms | -29ms | -14.831
| | P99| 935ms| 748ms | -187ms | -20.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 175ms| 152ms | -23ms | -13.132
| | P99| 2.014s| 1.89s | -124ms | -6.158
| searchAllChannels | Avg| 2.341s| 2.254s | -87ms | -3.716
| | P99| 9.472s| 9.48s | 8ms | 0.084
| searchFiles | Avg| 242ms| 626ms | 384ms | 158.749
| | P99| 249ms| 995ms | 746ms | 300.201
| searchGroupChannels | Avg| 68ms| 56ms | -12ms | -17.521
| | P99| 856ms| 566ms | -290ms | -33.890
| searchPostsInTeam | Avg| 226ms| 228ms | 2ms | 0.885
| | P99| 3.585s| 3.618s | 33ms | 0.920
| searchUsers | Avg| 219ms| 206ms | -13ms | -5.946
| | P99| 971ms| 972ms | 1ms | 0.103
| setPostReminder | Avg| 360ms| 69ms | -291ms | -80.828
| | P99| 4.45s| 925ms | -3.525s | -79.216
| unfollowThreadByUser | Avg| 132ms| 112ms | -20ms | -15.204
| | P99| 926ms| 906ms | -20ms | -2.160
| updateCategoriesForTeamForUser | Avg| 243ms| 398ms | 155ms | 63.681
| | P99| 2.23s| 2.419s | 189ms | 8.475
| updatePreferences | Avg| 17ms| 15ms | -2ms | -11.957
| | P99| 190ms| 177ms | -13ms | -6.839
| updateReadStateThreadByUser | Avg| 464ms| 388ms | -76ms | -16.370
| | P99| 4.293s| 3.964s | -329ms | -7.664
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 380ms| 367ms | -13ms | -3.424
| | P99| 994ms| 987ms | -7ms | -0.704
| upsertDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| viewChannel | Avg| 111ms| 97ms | -14ms | -12.603
| | P99| 1.195s| 986ms | -209ms | -17.487
